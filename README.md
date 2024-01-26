# Teste Técnico para Vaga de Backend

Antes de tudo, queremos expressar nossa gratidão pelo seu interesse em se juntar ao Grupo Adriano Cobuccio! Confira todas as informações essenciais para começar o seu teste logo abaixo.

## Antes de Começar:

- Crie um repositório no seu GitHub com um nome legal para o projeto mas não cite a empresa.
- Faça seus commits no seu repositório.
- Ao terminar tudo ou uma parte até o dia passado pelo recrutador, envie o link de acesso ao seu repositório para o recrutador responsável via email.
- Fique a vontade para perguntar qualquer dúvida aos recrutadores.

<br />

Que a sorte esteja com você! 🚀

## Necessidade:

João, um funcionário da empresa, precisa otimizar o processo de recebimento de pagamentos feitos no dia anterior por meio de um arquivo de texto específico. Atualmente, ele utiliza o Excel para manipulação eficiente dos dados, mas devido à necessidade de integração com outros serviços backend na empresa, ele busca uma solução mais robusta. Seu desafio é resolver este problema com uma api REST.

- O que o João disse: “Quero um sistema no qual eu posso fazer o upload de um arquivo e depois quero poder visualizar este arquivo de forma paginada, também quero poder apagar e editar dados caso eu veja alguma incoerência, após eu fazer esta verificação preciso confirmar estes dados e aí sim, eles nunca mais poderão ser apagados devido às auditorias constantes que temos aqui. Devido às auditorias, é necessário também que seja possível exportar estes dados via CSV. Os dados que retornamos quando temos auditorias é na casa dos milhares, então o sistema não pode ficar lento ao puxar este relatório. Não tenho problemas se demorar um pouco para que eu possa ter acesso aos dados”

<br />

# Requisitos:

### Upload de Arquivo:

Desenvolva uma funcionalidade que permita o upload de arquivos contendo os dados de pagamento.

### Visualização Paginada:

Implemente uma visualização paginada dos dados do arquivo após o upload.

### Edição e Exclusão de Dados:

Crie funcionalidades para editar e excluir dados, caso incoerências sejam identificadas durante a visualização.

### Confirmação e Auditoria:

Após a verificação, implemente um mecanismo de confirmação dos dados, tornando-os permanentes devido às auditorias frequentes.

### Exportação em CSV:

Desenvolva a capacidade de exportar os dados para um arquivo CSV, atendendo aos requisitos de auditoria.

### Formato do Arquivo do João:

- Os dados são recebidos no seguinte formato:
  - Nome (Máximo 15 caracteres) (espaços em branco à esquerda para caracteres vazios)
  - Idade (Máximo 4 caracteres) (zeros à esquerda para indicar campos vazios)
  - Endereço (Máximo 34 caracteres) (espaços em branco à esquerda para caracteres vazios)
  - CPF (Máximo 11 caracteres) (zeros à esquerda para indicar campos vazios)
  - Valor Pago (Máximo 16 caracteres) (zeros à esquerda para indicar campos vazios)
  - Data de Nascimento (Máximo 8 caracteres) (zeros à esquerda para indicar campos vazios)

### Exemplo de Linha no Arquivo:

```.txt
  Blair Bartell0070     8402 Wehner Rapids New Jaylen55373797384000000000000558220231223
```

### Instruções Adicionais:

Neste repositório tem um gerador de linhas em Javascript para facilitar seu teste (pasta: `generate_joao_file`) e poder testar os arquivos para enviar para a sua API. Será o mesmo que iremos gerar para rodar em sua API. Para roda-lo você precisará do Node JS em sua máquina e executar os comandos dentro da pasta “npm install” e “node index.js > arquivo_do_joao.txt”. Também já tem um arquivo gerado de exemplo para testar sua API na pasta “joao_file”.

### Observações:

Para este teste você pode utilizar as linguagens (Java, JavaScript (NodeJS), PHP, Python, Go ou C#)
Utilize Docker e deixe informações claras sobre como executar sua API.

### O que será avaliado:

- Documentação.
- Código limpo e organizado.
- Conhecimento de padrões de desenvolvimento de software.
- Saber argumentar sobre as suas escolhas.
- Modelagem de dados.
- Tratamento de erros.
- Arquitetura.
- Desacoplamento de componentes.
- Possibilidade de escalabilidade horizontal.

### O que não será avaliado:

- Frontend, será avaliado apenas a sua API.

### O que será um diferencial:

- Testes de Integração.
- Testes unitários.
- Documentação.
- Proposta de melhoria na forma que o requisito está sendo passado.
