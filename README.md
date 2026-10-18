# Def4cer
A Secure Version of CVE-2026-53787 Amasty Order Attribute File Upload Exploit,with the modification of file upload of txt to html.



Uma Versão Segura da CVE-2026-53787 Amasty Order Attribute File Upload Exploit,com a modificação do carregamento de arquivo do TXT para HTML.

## Detalhes e Como Utilizar

- Na Versão que eu peguei,havia uma conexão no python que fazia uma reverse shell,e colocava um backdoor.
- E Nisso,eu removi e por isso a versão do código é segura.
- além de que,eu adaptei-o pra arquivos html,então agora além de exploitar o site com vulnerabilidade da CVE-2026-53787,AOA File Upload,ele exploita com html.

## COMO UTILIZAR

No Linux:

- git clone https://github.com/elitexspam/Def4cer
- entre na pasta Def4cer,
- modifique com o bloco de notas ou libreoffice,etc.
- na "POC_FILENAME" adicione o nome do seu arquivo html,por exemplo:elite.html
- no "POC_CONTENT" dentro das """ """,adicione o seu código html,
- pegue sua lista de sites vulneráveis e renomeie de:alvos.txt.
- pronto pra uso.

## COMO EXECUTAR

```bash
cd Def4cer

python3 (ou python) message.py
```
Pronto,vai executar o python e digite:alvos.txt
depois,digite 1. e ele vai fazer o exploit.
