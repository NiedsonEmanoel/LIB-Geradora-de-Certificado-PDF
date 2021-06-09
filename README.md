# Geradora de Certificados em PDF
Biblioteca simples feita com o ejs com o instuito de gerar certificados em pdf.

## Para instalar:
```
npm i lib-geradora-de-certificado-pdf
```


## O código abaixo gera o seguinte certificado:
```
const certGenerator = require('lib-geradora-de-certificado-pdf');

(async () => {
    await certGenerator(
        'CERTIFICADO',
        'Confiro o presente certificado a',
        'Niedson Emanoel',
        'Por ter participado da criação da biblioteca',
        'Geradora de Certificados em PDF.',
        'As sugestões da comunidade são muito bem-vindas e sintam-se a vontade.',
        'Niedson Emanoel',
        'Programador Jr.',
        __dirname, 'cert.pdf'
    )
})()
```

<img src="asset1.png"/>


