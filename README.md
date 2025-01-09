# Ransomware de criptografia

### Configurando o local

- Criar pasta: ```mkdir ransomware```
  
![Alt text](./pasta.png "Optional title")

- Criar os arquivos txt e python:
```touch encrypter.py``` ```touch decrypter.py``` ```touch teste.txt```

![Alt text](./arquivos.png "Optional title")

### Criptografia

- Escrever os códigos e mensagem: ```nano encrypter.py``` ```nano decrypter.py``` ```nano teste.txt```
  
![Alt text](./escrever.png "Optional title")

- Encriptografar mensagem: ```python3 encrypter.py```

![Alt text](./encriptografar.png "Optional title")  

- Descriptografar mensagem: ```python3 decrypter.py```

![Alt text](./descriptografar.png "Optional title")

### Possível erro

- Durante a execução, se o módulo pyaes não estiver instalado no ambiente Python ocorrerar um erro de execução
```ModuleNotFoundError: No module named 'pyaes'```

- Para resolver é preciso instalar o pyaes:
```sudo apt update```
```sudo apt install python3-pip```

- As distribuições Linux mais recentes, incluindo Kali Linux, implementaram políticas que restringem a instalação de pacotes Python diretamente com pip em determinados ambientes.
- Para baixar com o pip utilizasse: ```pip3 install pyaes --break-system-packages```
