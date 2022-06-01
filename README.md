# Projeto da atividade 3:
 

1. Ao informar o CPF, deve-se chamar a API que busca um cadastro pelo documento: https://app.professordaniloalves.com.br/api/documentation#/Cadastro/81bd906c97113cd1f0b1905660e54883
2. Caso o cadastro já exista, deve-se exibir um modal perguntado ao usuário se ele deseja excluir ou alterar o cadastro. <br>
  • Caso escolha alterar, preencha todos os campos conforme retorno da API. (Dica, guarde o id em um input do tipo hidden, você terá que usar essa informação para atualizar o cadastro. (https://www.w3schools.com/tags/att_input_type_hidden.asp) <br>
  • Caso escolha excluir, chame a API de excluir um cadastro pelo documento: https://app.professordaniloalves.com.br/api/documentation#/Cadastro/d74a0d6d685f1033b3527d7015a4cd11 <br>
3. Caso o cadastro NÃO exista, siga com o cadastro normalmente.
4. TODAS as validações e funcionalidades das atividades 1 e 2 devem continuar funcionando, mesmo que seja para atualizar o cadastro. (Ex.: O tratamento de erro para retornos com status code http 422, enviar o formulário só se clicar em aceitar o termo, limpar os campos se der sucesso no envio)
5. Ao enviar o cadastro de atualização, deve-se chamar a API com o verbo PUT, responsável por atualizar o cadastro: https://app.professordaniloalves.com.br/api/documentation#/Cadastro/8ff76ab51bd515d90d374ef84331888d
