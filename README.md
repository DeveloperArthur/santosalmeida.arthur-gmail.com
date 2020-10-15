#Spring Security

Arquivos para **Proteger URL'S** : `SecurityConfigurations.java`

Arquivos para **Autenticar usuário ao logar** : `AutenticacaoService.java`, `SecurityConfigurations.java`, `Usuario.java`

Arquivos para **Devolver Token ao logar** : `AutenticacaoController.java`, `TokenService`

Arquivos para **Validar token** : `AutenticacaoViaTokenFilter.java`, `TokenService.java`, `SecurityConfigurations.java`

Criptografar senha: `String senhaCriptografada = new BCryptPasswordEncoder().encode(senha);` 