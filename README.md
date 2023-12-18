###Organizador de Arquivos por Mês###
Este script em Python oferece uma solução simples para organizar arquivos em uma pasta de origem com base em um conjunto predefinido de regras associadas a meses. Ele utiliza a biblioteca tkinter para interação com o usuário e os módulos os e os.path para manipulação de arquivos e diretórios.

Como Usar
Execute o script em um ambiente Python.
Uma janela será exibida solicitando que você escolha a "Pasta Origem" e a "Pasta Destino".
Após a seleção das pastas, o script percorrerá os arquivos na "Pasta Origem" e os moverá para subpastas correspondentes na "Pasta Destino" de acordo com as regras definidas.
Requisitos
Certifique-se de ter Python instalado em seu sistema. Além disso, as seguintes bibliotecas são necessárias:

bash
Copy code
pip install tk
Estrutura de Arquivos
O script organiza os arquivos com base em partes do nome associadas a meses. As regras são definidas no dicionário regras_arquivos. Por exemplo:

python
Copy code
regras_arquivos = {
    "jan": "Janeiro",
    "fev": "Fevereiro",
    "mar": "Março"
}
Neste exemplo, se o nome do arquivo contiver "jan", ele será movido para a pasta "Janeiro" na "Pasta Destino".

Exemplo de Uso
Suponha que a "Pasta Origem" contenha arquivos como "relatorio_jan.txt", "documento_fev.pdf", etc. Após a execução do script, esses arquivos serão organizados nas pastas correspondentes em "Pasta Destino".

Nota: Certifique-se de que as permissões de escrita são concedidas para as pastas relevantes.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar pull requests para melhorar este script.

Observação: Este script assume que os arquivos de entrada seguem um padrão específico relacionado aos meses. Modifique as regras no dicionário conforme necessário para atender às suas necessidades específicas.
