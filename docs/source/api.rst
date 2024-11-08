API
===

Most data in ChemoPar-db is available programmatically via a REST API.

List of API endpoints
---------------------

Each endpoint is described in the `API reference`_.

.. _API reference: https://chemopar-db.net/api/


API sample scripts
------------------

Using Python 3
^^^^^^^^^^^^^^^^^^^^^^^

This is the recommended approach. Requires installation of the `requests library`_.

.. _requests library: https://requests.readthedocs.io

::

    import requests

    def get_protein_details():
        url = "https://chemopar-db.net/api/protein_details/"
        response = requests.get(url)

        if response.status_code == 200:
            # Assuming the response contains JSON data, you can use response.json() to access the data
            protein_data = response.json()
            
            # Process or save the protein_data as needed
            print("Protein details retrieved:", protein_data)
        else:
            print("Failed to retrieve protein details. Status code:", response.status_code)

    # Example usage:
    get_protein_details()

Python 3 with urllib
^^^^^^^^^^^^^^^^^^^^

::

    import urllib.request
    import json
    
    def get_protein_details():
        url = "https://chemopar-db.net/api/protein_details/"
        
        try:
            with urllib.request.urlopen(url) as response:
                data = json.loads(response.read().decode("utf-8"))
                # Assuming the response contains JSON data, you can use json.loads to access the data

                # Process or save the data as needed
                print("Protein details retrieved:", data)
        except urllib.error.HTTPError as e:
            print("Failed to retrieve protein details. Status code:", e.code)
        except urllib.error.URLError as e:
            print("Error connecting to the server:", e.reason)

    # Example usage:
    get_protein_details()
