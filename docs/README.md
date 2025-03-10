# How to build website

## Installation

First install mkdocs using pip

```
pip install mkdocs 
```

Once installed, make sure to add the path to mkdocs to the systems environment variables. The installation process might print warnings about this already.
On windows this is found in *Advanced system settings* $\rightarrow$ *System Properties* $\rightarrow$ *Environment Variables*.
Look for the ``Path`` variable under *System variables* and check for the directory containing the mkdocs executable. If it does not exist add it to the ``Path`` variable.

Continue installing the following packages using pip

- table reader

  ```sh
  pip install mkdocs-table-reader-plugin 
  ```

- markdown include

  ```sh
  pip install markdown-include 
  ```

- mkdocs material

  ```sh
  pip install mkdocs-material
  ```

- openpyxl

  ```sh
  pip install openpyxl
  ```

## Run website locally

All configurations for the website are stored in the ``mkdocs.yml`` on the toplevel of the repo.

To run it locally simply run the following from the HelMoRo folder.

```
mkdocs serve -a localhost:8888
```

Make sure the port you are using is open.

Now the website can be accessed locally at http://localhost:8888

On Github within the Repo Settings under the Pages Tab you can access and change the published site preferences.

