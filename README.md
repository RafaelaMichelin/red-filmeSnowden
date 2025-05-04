# Redação Técnica, Filme: Snowden  


## Quais cuidados um desenvolvedor front- end deve ter ao lidar com dados sensíveis em um site ou sistema? 

### Ao lidar com dados sensíveis em sites e sistemas, é importante que o programador front- end adote medidas de segurança para proteger a privacidade dos usuários. Dados como CPF, endereço, e-mail e nome completo são considerados sensíveis, pois podem ser utilizados em fraudes, roubo de identidade ou outras formas de violação de privacidade. Por isso, o uso do protocolo HTTPS é indispensável, garantindo que as informações trafeguem pela internet de forma criptografada, evitando interceptações. Também é responsabilidade do front- end garantir que o usuário seja claramente informado sobre como seus dados serão utilizados. Isso pode ser feito por meio de banners, modais ou links para a política de privacidade, que expliquem a finalidade da coleta de dados. 

 ## Os dados sensíveis no qual o programador fronte- end necessita de mais cuidado são: 

## <!-- CPF/CNPJ: é um dado pessoal e identificador único no Brasil-->  

 ### <label for="">CPF/CNPJ</label> 

### <input type= "text" name="cpf-cnpj" placeholder="CPF-CNPJ"> 
 

## <!-- Nome completo: é um dado pessoal básico, podendo ser usado para identificação-->  

### <label for="">Nome</label> 

### <input type= "text" name="nome" placeholder= "Nome"> 


## <!-- O campo E-mail pode ser usado em ataques se for exposto --> 

### <label for="">E-mail</label> 

### <input type="email" name="email" placeholder="E-mail"> 


## <!-- Endereço Residencial: é um dado sensível por ser informado a localização-->  

### <label for="">Endereço</label> 

### <input type= "text" name="endereço" placeholder= "Endereco"> 

  

## Lista de cuidados necessários: 

 

### Informar o usuário sobre como os dados serão usados 

### Utilizar HTTPS sempre que houver envio de dados (Back-end)

### Evitar armazenar senhas em campos visíveis

### Nunca salvar dados sensíveis no LocalStorage

### Mascarar campos sensíveis como CPF, telefone e cartão

### Evitar expor dados confidenciais no console do navegador ou no código-fonte
