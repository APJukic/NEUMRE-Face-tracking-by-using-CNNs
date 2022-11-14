# NEUMRE-projekt

Face tracking by using CNNs


### Skidanje podatkovnog skupa
Prvo treba skinuti podatkovni skup: skup za treniranje, validaciju, testiranje i odgovarajuće oznake (link: https://shuoyang1213.me/WIDERFACE/)

Skup za treniranje: https://drive.google.com/file/d/15hGDLhsx8bLgLcIRD5DhYt5iBxnjNF1M/view?usp=sharing
Skup za validaciju: https://drive.google.com/file/d/1GUCogbp16PMGa39thoMMeWxp7Rp5oM8Q/view?usp=sharing
Skup za testiranje: https://drive.google.com/file/d/1HIfDbVEWKmsYKJZm4lchTBDLW5N7dY5T/view?usp=sharing
Skup oznaka: https://shuoyang1213.me/WIDERFACE/support/bbx_annotation/wider_face_split.zip

Te skupove treba raspakirati u direktorij projekta, točnije u folder "widerface" unutar projektnog direktorija. 
Tada bi direktorij trebao izgledati ovako:

NEUMRE-projekt:
    .git
    README.md
    main.ipynb
    widerface/
        wider_face_split/
        WIDER_test/
        WIDER_train/
        WIDER_val/
