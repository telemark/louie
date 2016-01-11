# Distribusjon

Hente varsel fra kø/API for å motta varsel

Roy
    Adresseoppslag
        input: fødselsnummer, foresatte (true/false)
        dsf
            [node-dsf]()
        foresatte
            [node-def]()
        hemmelig
            stringsjekk mot dsf
            kontaktperson 360
                [node-p360]()
        output:
            Fødselsnummer
            Navn (firstname/lastname)
            Adresse (adresse/zip/city)
            Postadresse
            Hemmelig (true/false)
            Foresatte: false eller object med navn, adresse, hemmelig
    
Generere varsel
    [tfk-template-to-pdf](https://github.com/telemark/tfk-template-to-pdf)
    [docxtemplater-webservice-docker](https://github.com/telemark/docxtemplater-webservice-docker)
        [templaterService](https://templater.service.t-fk.no/)
    [converttopdf-webservice-docker](https://github.com/telemark/converttopdf-webservice-docker)
        [pdfconvertService](https://pdfconvert.service.t-fk.no/)

SvarUT
    [node-svarut](https://github.com/telemark/node-svarut)