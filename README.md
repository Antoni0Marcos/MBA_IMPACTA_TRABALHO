# Comandos Git

Aqui está uma lista de comandos Git usados no fluxo de trabalho:

1. **Inicialize um novo repositório Git**
    ```bash
    git init
    ```

2. **Configure o nome de usuário global**
    ```bash
    git config --global user.name "antonio.marcos"
    ```

3. **Configure o e-mail global**
    ```bash
    git config --global user.email "dearaujomarcos@outlook.com"
    ```

4. **Crie um arquivo `arquivo.txt` com o conteúdo `01`**
    ```bash
    echo 01 > arquivo.txt
    ```

5. **Adicione o arquivo ao estágio**
    ```bash
    git add arquivo.txt
    ```

6. **Verifique o status dos arquivos**
    ```bash
    git status
    ```

7. **Faça um commit com a mensagem "git add example - arquivo.txt"**
    ```bash
    git commit -m "git add example - arquivo.txt"
    ```

8. **Atualize o arquivo `arquivo.txt` com o conteúdo `02`**
    ```bash
    echo 02 > arquivo.txt
    ```

9. **Veja as diferenças não preparadas para commit**
    ```bash
    git diff
    ```

10. **Adicione o arquivo ao estágio novamente**
    ```bash
    git add arquivo.txt
    ```

11. **Verifique o status dos arquivos**
    ```bash
    git status
    ```

12. **Veja as diferenças preparadas para commit**
    ```bash
    git diff --staged
    ```

13. **Atualize o arquivo `arquivo.txt` com o conteúdo `03`**
    ```bash
    echo 03 > arquivo.txt
    ```

14. **Veja as diferenças não preparadas para commit**
    ```bash
    git diff
    ```

15. **Restaure o arquivo do estágio**
    ```bash
    git restore --staged arquivo.txt
    ```

16. **Verifique o status dos arquivos**
    ```bash
    git status
    ```

17. **Faça um commit com a mensagem "add example - arquivo.txt"**
    ```bash
    git commit -m "add example - arquivo.txt"
    ```

18. **Veja o histórico de commits**
    ```bash
    git log
    ```

19. **Adicione `*.txt` ao `.gitignore`**
    ```bash
    echo "*.txt" >> .gitignore
    ```

20. **Crie um novo arquivo `novo.txt` com o conteúdo `new`**
    ```bash
    echo new > novo.txt
    ```

21. **Verifique o status dos arquivos**
    ```bash
    git status
    ```

22. **Faça um commit com a mensagem "first commit"**
    ```bash
    git commit -m "first commit"
    ```

23. **Renomeie a branch atual para `main`**
    ```bash
    git branch -M main
    ```

24. **Faça o push das alterações para o repositório remoto**
    ```bash
    git push -u origin main
    ```

25. **Adicione o arquivo `README.md` ao estágio**
    ```bash
    git add README.md
    ```

26. **Mostre o histórico de comandos do terminal**
    ```bash
    history
    ```
