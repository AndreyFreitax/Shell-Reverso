# 🐚 Shell Reverso com GSocket

![Captura de Tela (7)](https://github.com/user-attachments/assets/522b4a3a-dcf2-4ea9-8e30-b2e86ebcda26)


Este repositório contém um script em Python que utiliza a ferramenta [GSocket](https://gsocket.io) para criar uma **conexão reversa segura** e estável, mesmo atrás de NATs ou firewalls. Ideal para fins educacionais, testes de penetração ou demonstrações de segurança ofensiva, O script baixa um código da internet (do site gsocket.io) e executa ele no seu computador via terminal, salvando o que ele imprimir no arquivo output.txt. Isso pode permitir que alguém se conecte remotamente ao seu computador.

---

## ⚙️ Requisitos

- Python 3
- cURL
- Permissão para execução de comandos no terminal
- Conexão com a internet

---

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/AndreyFreitaz/Shell-Reverso.git
cd Shell-Reverso
python3 gsocket.py
cat output.txt
```

ou
```bash
wget https://raw.githubusercontent.com/Andreyftg/Shell-Reverso/refs/heads/main/gsocket.py
python3 gsocket.py
cat output.txt
```


