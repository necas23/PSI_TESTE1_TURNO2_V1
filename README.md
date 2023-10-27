# Teste de PSI 1 - Turno 2 - Versão 1

## Informação do aluno

    Nome: Rodrigo Silva

Teste termina às 13:25.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    bool x = true && false;
    x |= 2 < 5;
    
    Console.WriteLine(x);

P1 - Resposta

    Quando corrido o código apresenta a palavra "True" porque o 2 é menor que 5

### P2. Considera o seguinte código com um *bug*

    short s = long.MaxValue;

    Console.WriteLine(s);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    Foi necessário trocar o "long.MaxValue;" para "short.MaxValue;" para o código não apresentar nenhum erro.

### P3. Escreve um programa que solicite ao utilizador dois números reais e apresente o resultado do primeiro (base) elevado ao segundo (expoente). Não podes usar um método da classe Math para obter o resultado

P3 - Resposta

    

### P4. Estás na pasta raiz do teu repositório local, onde atualizaste um ficheiro de nome 'Classes.cs'. Queres enviar **apenas** esta atualização para o teu repositório remoto. Indica os comandos necessários. A mensagem de commit deve ser apropriada

P4 - Resposta

    git status
    git add Classes.cs 
    git commit -m "Atualizar ficheiro Classes.cs"
    git push
