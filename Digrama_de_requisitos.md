flowchart TD

    A[Usuário Pessoa Física] -->|Usa| S[Sistema Minibank]
    B[Usuário Pessoa Jurídica] -->|Usa| S
    C[Administrador/Suporte] -->|Gerencia| S

    %% Módulos Principais
    S --> M1[Onboarding e Cadastro]
    S --> M2[Gerenciamento de Contas]
    S --> M3[Transações Financeiras]
    S --> M4[Cartão Virtual]
    S --> M5[Controle Financeiro]
    S --> M6[Notificações]
    S --> M7[Segurança e Auditoria]

    %% Onboarding
    M1 --> R1[Validação automática de CPF/CNPJ]
    M1 --> R2[Upload e análise de documentos]
    M1 --> R3[Criação de senha e autenticação]
    M1 --> R4[Criação de conta PF ou PJ]

    %% Gerenciamento de Contas
    M2 --> R5[Conta Corrente]
    M2 --> R6[Conta Poupança]
    M2 --> R7[Conta Empresarial]
    M2 --> R8[Visualização de saldo e extrato]

    %% Transações
    M3 --> R9[Pix - enviar/receber]
    M3 --> R10[Pagamento de boletos]
    M3 --> R11[Transferências bancárias]
    M3 --> R12[Agendamentos]

    %% Cartão Virtual
    M4 --> R13[Criação do cartão virtual]
    M4 --> R14[Controle de limites]
    M4 --> R15[Bloquear/Desbloquear]
    M4 --> R16[Gerar novo número (tokenização)]

    %% Controle Financeiro
    M5 --> R17[Relatórios mensais]
    M5 --> R18[Orçamentos]
    M5 --> R19[Categorias de gastos]

    %% Notificações
    M6 --> R20[Transações]
    M6 --> R21[Avisos de orçamento]
    M6 --> R22[Segurança]

    %% Segurança
    M7 --> R23[Autenticação multifator]
    M7 --> R24[Registro de logs]
    M7 --> R25[Validação antifraude]
