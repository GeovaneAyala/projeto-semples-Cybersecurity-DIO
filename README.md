```markdown
# Entendendo um Ransomware na Prática com Python

Este projeto é um desafio prático desenvolvido durante o bootcamp da **Digital Innovation One (DIO)**. O objetivo é compreender, em ambiente controlado, o funcionamento básico do processo de criptografia e descriptografia de arquivos utilizado em ataques do tipo Ransomware para fins educacionais e de conscientização sobre Cibersegurança.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3**
- **pyaes**: Biblioteca para implementação do algoritmo de criptografia AES (Advanced Encryption Standard).

---

## 📂 Estrutura do Repositório

- `encrypter.py`: Script responsável por ler o arquivo de teste, criptografar seu conteúdo utilizando o algoritmo AES e salvar a versão criptografada.
- `decrypter.py`: Script responsável por ler o arquivo criptografado, reverter o processo com a chave correspondente e restaurar o arquivo original.
- `teste.txt`: Arquivo de exemplo utilizado no teste do processo de criptografia e restauração.

---

## 🚀 Como Executar o Projeto

### Pró-requisitos

Certifique-se de ter o Python 3 instalado no seu ambiente. Instale a biblioteca necessária executando:

```bash
pip install pyaes

```

### Passo a Passo

1. **Criptografar o arquivo:**
Execute o script de criptografia para transformar o arquivo de teste em um formato cifrado:
```bash
python3 encrypter.py

```


2. **Descriptografar o arquivo:**
Execute o script de descriptografia para reverter o arquivo ao seu estado original:
```bash
python3 decrypter.py

```



---

## ⚠️ Isenção de Responsabilidade (Disclaimer)

Este projeto tem fins estritamente **educacionais** e de estudo acadêmico, conforme proposto no programa da DIO. O uso deste conhecimento para fins maliciosos é ilegal e não recomendado.

```

---
