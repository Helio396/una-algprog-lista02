--sensor_re.png--

INÍCIO
   |
Ler distância
   |
distância < 0.5 ?
   | SIM ------------------> Bipe contínuo + "PARE"
   |
   NÃO
   |
distância <= 2 ?
   | SIM ------------------> Bipe intermitente
   |
   NÃO
   |
Sem som
   |
  FIM

  _________________//____________________

  --filtro_insta.png--

  INÍCIO
   |
Usuário escolhe foto
   |
Aplicar filtro P&B?
   | SIM ------> Aplicando filtro preto e branco
   | NÃO -----> Mantendo a foto original
   |
Postar agora?
   | SIM ------> Enviando foto para o servidor
   | NÃO -----> Salvando foto na galeria
   |
  FIM


  _________________//___________________


--execicio_saque.txt--

INÍCIO
   |
Ler saldo_disponivel
   |
Ler valor_saque
   |
valor_saque <= saldo_disponivel ?
   | SIM ----------------> Atualiza o saldo e
   |                      Entrega notas
   |
   | NÃO ----------------> Mostrar "Saldo insuficiente"
   |
  FIM
