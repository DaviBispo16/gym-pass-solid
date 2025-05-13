# APP

Gympass Style App


## RFs (Requisitos funcionais)
- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil do usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possível buscar academias próximas;
- [ ] Deve ser possível buscar academais pelo nome;
- [ ] Deve ser possível realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de uma usuário;
- [ ] Deve ser possível cadastrar uma academia;

## RNs (Regras de negócio)
- [ ] O usuário não deve poder de cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado até 20min depois de ser criado;
- [ ] O check-in só pode ser validado por um administrador;
- [ ] O check-in só pode ser cadastrado por administradores;

## RNFs (Requisitos não-funcionais)
- [ ] A senha do usuário precisar estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco de dados;
- [ ] Todas listas de dados preecisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);