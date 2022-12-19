# example
example code and design

And the directory structure has to be the following:
```
    .
    ├── main.py                
    ├── README.md
    ├── parameters.yaml       
    ├── LICENSE
    ├── trained_models          # Trained models
    ├── src                     # Source files
    └── data                    # Data files
        ├── ascii          # text files that contain the written text
        |   ├── a01
        |   |   ├── a01-000
        |   |   |   ├── a01-000u.txt
        |   |   |   └── a01-000x.txt
        |   |   └── ...
        |   └── ...
        └── lineStrokes    # xml files that contain the strokes
            ├── a01
            |   ├── a01-000
            |   |   ├── a01-000u-01.xml
            |   |   └── a01-000u-02.xml
            |   |   └── ...
            |   └── ...
            └── ...
    
```
