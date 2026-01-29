<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido de Refeição</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);
            width: 100%;
            max-width: 500px;
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        .header h1 {
            font-size: 28px;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .header p {
            font-size: 13px;
            opacity: 0.9;
        }

        .form-content {
            padding: 30px;
        }

        .form-group {
            margin-bottom: 24px;
        }

        label {
            display: block;
            font-size: 13px;
            font-weight: 600;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        label .required {
            color: #e74c3c;
        }

        input[type="text"],
        input[type="date"],
        input[type="number"],
        select,
        textarea {
            width: 100%;
            padding: 12px 14px;
            border: 1px solid #ddd;
            border-radius: 6px;
            font-family: inherit;
            font-size: 14px;
            transition: all 0.3s ease;
        }

        input[type="text"]:focus,
        input[type="date"]:focus,
        input[type="number"]:focus,
        select:focus,
        textarea:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }

        input[type="text"]::placeholder,
        textarea::placeholder {
            color: #95a5a6;
        }

        select {
            appearance: none;
            background-image: url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3e%3cpolyline points='6 9 12 15 18 9'%3e%3c/polyline%3e%3c/svg%3e");
            background-repeat: no-repeat;
            background-position: right 12px center;
            background-size: 20px;
            padding-right: 40px;
            cursor: pointer;
        }

        .radio-group {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }

        .radio-item {
            display: flex;
            align-items: center;
            gap: 10px;
            cursor: pointer;
        }

        input[type="radio"] {
            cursor: pointer;
            width: 18px;
            height: 18px;
            accent-color: #667eea;
        }

        .radio-item label {
            margin: 0;
            font-weight: 500;
            color: #34495e;
            cursor: pointer;
        }

        textarea {
            resize: vertical;
            min-height: 100px;
            font-size: 13px;
        }

        .button-group {
            display: flex;
            gap: 12px;
            margin-top: 30px;
        }

        .autocomplete-container {
            position: relative;
            width: 100%;
        }

        .sugestoes-list {
            position: absolute;
            top: 100%;
            left: 0;
            right: 0;
            background: white;
            border: 1px solid #ddd;
            border-top: none;
            border-radius: 0 0 6px 6px;
            list-style: none;
            max-height: 250px;
            overflow-y: auto;
            display: none;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .sugestoes-list.ativa {
            display: block;
        }

        .sugestoes-list li {
            padding: 12px 14px;
            cursor: pointer;
            border-bottom: 1px solid #f0f0f0;
            font-size: 14px;
            color: #34495e;
            transition: all 0.2s ease;
        }

        .sugestoes-list li:last-child {
            border-bottom: none;
        }

        .sugestoes-list li:hover,
        .sugestoes-list li.selecionado {
            background-color: #ecf0f1;
            padding-left: 20px;
        }

        .sugestoes-list li .highlight {
            font-weight: 700;
            color: #667eea;
        }

        button {
            flex: 1;
            padding: 12px 20px;
            border: none;
            border-radius: 6px;
            font-size: 14px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-submit {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }

        .btn-submit:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .btn-reset {
            background: #ecf0f1;
            color: #34495e;
        }

        .btn-reset:hover {
            background: #d5dbdb;
        }

        .checkmark {
            font-size: 18px;
        }

        /* Modal de Sucesso */
        .modal-overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: 9999;
            justify-content: center;
            align-items: center;
            animation: fadeIn 0.3s ease;
        }

        .modal-overlay.ativo {
            display: flex;
        }

        .modal-sucesso {
            background: white;
            border-radius: 16px;
            padding: 40px;
            max-width: 450px;
            text-align: center;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            animation: slideUp 0.4s ease;
            position: relative;
        }

        .sucesso-icon {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 24px;
            font-size: 48px;
            animation: scaleIn 0.5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
        }

        .sucesso-titulo {
            font-size: 28px;
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 12px;
        }

        .sucesso-mensagem {
            font-size: 15px;
            color: #7f8c8d;
            margin-bottom: 24px;
            line-height: 1.6;
        }

        .dados-resumo {
            background: #f8f9fa;
            border-radius: 12px;
            padding: 16px;
            margin-bottom: 24px;
            text-align: left;
            max-height: 200px;
            overflow-y: auto;
        }

        .dados-item {
            display: flex;
            justify-content: space-between;
            padding: 8px 0;
            font-size: 13px;
            border-bottom: 1px solid #e0e0e0;
        }

        .dados-item:last-child {
            border-bottom: none;
        }

        .dados-label {
            font-weight: 600;
            color: #34495e;
        }

        .dados-valor {
            color: #667eea;
            font-weight: 500;
        }

        .sucesso-botoes {
            display: flex;
            gap: 12px;
        }

        .btn-novo-pedido {
            flex: 1;
            padding: 12px 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 14px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-novo-pedido:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .btn-fechar-modal {
            flex: 1;
            padding: 12px 20px;
            background: #ecf0f1;
            color: #34495e;
            border: none;
            border-radius: 8px;
            font-size: 14px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-fechar-modal:hover {
            background: #d5dbdb;
        }

        /* Confete */
        .confete {
            position: fixed;
            width: 10px;
            height: 10px;
            background: #667eea;
            pointer-events: none;
            z-index: 9998;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes scaleIn {
            from {
                opacity: 0;
                transform: scale(0.5);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes cair {
            to {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🍽️ Pedido de Refeição</h1>
            <p>Sistema de Almoxo e Jantar - Brasil Digital Telecom</p>
        </div>

        <form class="form-content" id="pedidoForm">
            <!-- Seu Nome com Autocomplete -->
            <div class="form-group">
                <label for="nome">Seu Nome <span class="required">*</span></label>
                <div class="autocomplete-container">
                    <input 
                        type="text" 
                        id="nome" 
                        name="nome" 
                        placeholder="Comece digitando seu nome..."
                        autocomplete="off"
                        required
                    >
                    <ul id="sugestoes" class="sugestoes-list"></ul>
                </div>
            </div>

            <!-- Equipe / Empresa -->
            <div class="form-group">
                <label for="equipe">Equipe / Empresa <span class="required">*</span></label>
                <select id="equipe" name="equipe" required>
                    <option value="">-- Selecione --</option>
                    <option value="brasil-digital">Brasil Digital - BD</option>
                    <option value="matias-engenharia">Matias Engenharia - ME</option>
                    <option value="rr364">RR.364 Serviço</option>
                </select>
            </div>

            <!-- Data do Serviço -->
            <div class="form-group">
                <label for="data">Data do Serviço <span class="required">*</span></label>
                <input 
                    type="date" 
                    id="data" 
                    name="data"
                    required
                >
            </div>

            <!-- Onde será feito o serviço -->
            <div class="form-group">
                <label for="local">Onde será feito o serviço? <span class="required">*</span></label>
                <input 
                    type="text" 
                    id="local" 
                    name="local" 
                    placeholder="Ex: Campo, escritório, etc."
                    required
                >
            </div>

            <!-- O que está solicitando -->
            <div class="form-group">
                <label>O que está solicitando? <span class="required">*</span></label>
                <div class="radio-group">
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="almoco" 
                            name="tipoRefeicao" 
                            value="almoco"
                            required
                        >
                        <label for="almoco">🍽️ Almoço</label>
                    </div>
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="jantar" 
                            name="tipoRefeicao" 
                            value="jantar"
                        >
                        <label for="jantar">🌙 Jantar</label>
                    </div>
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="ambos" 
                            name="tipoRefeicao" 
                            value="ambos"
                        >
                        <label for="ambos">👥 Ambos</label>
                    </div>
                </div>
            </div>

            <!-- Por que está pedindo refeição -->
            <div class="form-group">
                <label>Por que está pedindo refeição? <span class="required">*</span></label>
                <div class="radio-group">
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="servico-campo" 
                            name="motivo" 
                            value="servico-campo"
                            required
                        >
                        <label for="servico-campo">Serviço em campo</label>
                    </div>
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="nao-tempo" 
                            name="motivo" 
                            value="nao-tempo"
                        >
                        <label for="nao-tempo">Não deu tempo de voltar para base</label>
                    </div>
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="servico-estendido" 
                            name="motivo" 
                            value="servico-estendido"
                        >
                        <label for="servico-estendido">Serviço estendido</label>
                    </div>
                    <div class="radio-item">
                        <input 
                            type="radio" 
                            id="outro" 
                            name="motivo" 
                            value="outro"
                        >
                        <label for="outro">Outro</label>
                    </div>
                </div>
            </div>

            <!-- Valor da Refeição -->
            <div class="form-group">
                <label for="valor">Valor da Refeição (R$) <span class="required">*</span></label>
                <input 
                    type="text" 
                    id="valor" 
                    name="valor" 
                    placeholder="Ex: 45,00"
                    required
                >
            </div>

            <!-- Observação -->
            <div class="form-group">
                <label for="observacao">Observação (opcional)</label>
                <textarea 
                    id="observacao" 
                    name="observacao" 
                    placeholder="Adicione observações ou detalhes adicionais..."
                ></textarea>
            </div>

            <!-- Botões -->
            <div class="button-group">
                <button type="submit" class="btn-submit">
                    <span class="checkmark">✓</span> Enviar Pedido
                </button>
                <button type="reset" class="btn-reset">
                    Limpar
                </button>
            </div>
        </form>

        <!-- Modal de Sucesso -->
        <div id="modalSucesso" class="modal-overlay">
            <div class="modal-sucesso">
                <div class="sucesso-icon">✓</div>
                <h2 class="sucesso-titulo">Pedido Enviado!</h2>
                <p class="sucesso-mensagem">
                    Seu pedido de refeição foi registrado com sucesso.
                </p>
                
                <div class="dados-resumo" id="resumoPedido"></div>

                <div class="sucesso-botoes">
                    <button class="btn-novo-pedido" id="btnNovoPedido">
                        ➕ Novo Pedido
                    </button>
                    <button class="btn-fechar-modal" id="btnFecharModal">
                        Fechar
                    </button>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Lista de colaboradores
        const colaboradores = [
            'IURY LOURRAN FERNANDES CARDOSO',
            'EMERSON SOARES PINTO',
            'JOSE FRANCISCO DA SILVA MUNIZ',
            'MANOEL PINTO',
            'ANDERSON APARECIDO DE SOUZA',
            'ARMANDO PEREIRA DA COSTA',
            'ALBERTINO FERREIRA COSTA',
            'MARCOS AGEU BARBOZA DE ARAUJO',
            'FRANCISCO ROCHA DOS SANTOS',
            'JOAO MAIDSON MENDES MOTA',
            'MARCOS HENRIQUE BITECOURT DE FREITAS',
            'ANTONIO CARLOS PEREIRA DA COSTA',
            'MARCELO AUGUSTO SILVA',
            'ANDRE PEREIRA MENEZES',
            'FLAERTE SILVA DANTAS',
            'ALEX ALVES FREITAS COSTA',
            'FLAVIO GABRIEL PESSOA BARBOSA',
            'RENAN DINIZ DA SILVA',
            'ANDERSON FREITAS NOE',
            'EVERTON VINICIUS ZAINIDIN DOS SANTOS',
            'ALESANDRO PANTOJA FLORENTINO',
            'MARCELO LIMA DA SILVA TEIXEIRA',
            'ADRIELYTON MANOEL DA COSTA',
            'AIRTON FREIRE DA SILVA',
            'MAQUESSOEL MARQUES DA SILVA',
            'FRANCIEL MACHADO CHAVES',
            'HUILLAN WILKENS DE ALMEIDA',
            'ARTHUR MARTINS QUEIROZ',
            'MARLON BRANDON ARAUJO PAZ',
            'BAILTON KLEY CHAGAS DA COSTA',
            'RIMOHÃN RENAN FEITOSA FIGUEIRA',
            'BRENNO BARROS',
            'RONILSON MATIAS DO NASCIMENTO',
            'ALAN DUMAY DE FREITAS',
            'MATHEUS EDUARDO LOPES PEREIRA',
            'JOSE RONALDO PEREIRA BARROS',
            'ALAN HENRIQUE TAVARES GONCALVES',
            'FABRICIO BELEZA OLIVEIRA',
            'RENAN BRUNO DA SILVA IBERNEGARA'
        ];

        // Variáveis do autocomplete
        const inputNome = document.getElementById('nome');
        const listaSugestoes = document.getElementById('sugestoes');
        let indiceAtual = -1;

        // Evento de digitação no campo de nome
        inputNome.addEventListener('input', function(e) {
            const termo = e.target.value.trim().toUpperCase();
            
            if (termo.length === 0) {
                listaSugestoes.classList.remove('ativa');
                return;
            }

            // Filtra colaboradores que contêm o termo digitado
            const filtrados = colaboradores.filter(nome => 
                nome.includes(termo)
            ).slice(0, 15); // Limita a 15 sugestões

            // Se encontrou sugestões, mostra
            if (filtrados.length > 0) {
                renderizarSugestoes(filtrados, termo);
                listaSugestoes.classList.add('ativa');
                indiceAtual = -1;
            } else {
                listaSugestoes.classList.remove('ativa');
            }
        });

        // Função para renderizar as sugestões com destaque
        function renderizarSugestoes(sugestoes, termo) {
            listaSugestoes.innerHTML = '';

            sugestoes.forEach((nome, index) => {
                const li = document.createElement('li');
                
                // Destaca a parte do nome que corresponde à busca
                const regex = new RegExp(`(${termo})`, 'gi');
                const nomeComDestaque = nome.replace(
                    regex,
                    '<span class="highlight">$1</span>'
                );
                
                li.innerHTML = nomeComDestaque;
                li.setAttribute('data-index', index);
                
                // Seleciona sugestão ao clicar
                li.addEventListener('click', function() {
                    inputNome.value = nome;
                    listaSugestoes.classList.remove('ativa');
                });

                // Hover nas sugestões
                li.addEventListener('mouseenter', function() {
                    document.querySelectorAll('.sugestoes-list li').forEach(item => {
                        item.classList.remove('selecionado');
                    });
                    li.classList.add('selecionado');
                });

                listaSugestoes.appendChild(li);
            });
        }

        // Navegação por teclado (setas para cima/baixo, Enter)
        inputNome.addEventListener('keydown', function(e) {
            const items = document.querySelectorAll('.sugestoes-list li');
            
            if (e.key === 'ArrowDown') {
                e.preventDefault();
                indiceAtual = Math.min(indiceAtual + 1, items.length - 1);
                atualizarSelecao(items);
            } else if (e.key === 'ArrowUp') {
                e.preventDefault();
                indiceAtual = Math.max(indiceAtual - 1, -1);
                atualizarSelecao(items);
            } else if (e.key === 'Enter' && indiceAtual >= 0) {
                e.preventDefault();
                items[indiceAtual].click();
            } else if (e.key === 'Escape') {
                listaSugestoes.classList.remove('ativa');
            }
        });

        function atualizarSelecao(items) {
            items.forEach((item, index) => {
                item.classList.remove('selecionado');
                if (index === indiceAtual) {
                    item.classList.add('selecionado');
                    item.scrollIntoView({ block: 'nearest' });
                }
            });
        }

        // Fecha as sugestões ao clicar fora
        document.addEventListener('click', function(e) {
            if (e.target !== inputNome) {
                listaSugestoes.classList.remove('ativa');
            }
        });

        // Formata o campo de valor para moeda brasileira
        const valorInput = document.getElementById('valor');
        valorInput.addEventListener('input', function(e) {
            let value = e.target.value.replace(/\D/g, '');
            if (value) {
                value = (parseInt(value) / 100).toLocaleString('pt-BR', {
                    minimumFractionDigits: 2,
                    maximumFractionDigits: 2
                });
            }
            e.target.value = value;
        });

        // Define a data de hoje como padrão
        const dataInput = document.getElementById('data');
        const hoje = new Date().toISOString().split('T')[0];
        dataInput.value = hoje;

        // Manipula o envio do formulário
        const form = document.getElementById('pedidoForm');
        const modalSucesso = document.getElementById('modalSucesso');
        const btnNovoPedido = document.getElementById('btnNovoPedido');
        const btnFecharModal = document.getElementById('btnFecharModal');
        const resumoPedido = document.getElementById('resumoPedido');

        form.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Coleta os dados
            const dados = {
                nome: document.getElementById('nome').value,
                equipe: document.getElementById('equipe').value,
                data: document.getElementById('data').value,
                local: document.getElementById('local').value,
                tipoRefeicao: document.querySelector('input[name="tipoRefeicao"]:checked').value,
                motivo: document.querySelector('input[name="motivo"]:checked').value,
                valor: document.getElementById('valor').value,
                observacao: document.getElementById('observacao').value || '—'
            };

            // Mapeia valores para exibição
            const mapeamento = {
                tipoRefeicao: {
                    almoco: '🍽️ Almoço',
                    jantar: '🌙 Jantar',
                    ambos: '👥 Ambos'
                },
                motivo: {
                    'servico-campo': 'Serviço em campo',
                    'nao-tempo': 'Não deu tempo de voltar para base',
                    'servico-estendido': 'Serviço estendido',
                    'outro': 'Outro'
                }
            };

            console.log('Dados do Pedido:', dados);

            // Exibe o modal com os dados
            exibirModalSucesso(dados, mapeamento);

            // Cria efeito de confete
            criarConfete();
        });

        // Função para exibir modal de sucesso
        function exibirModalSucesso(dados, mapeamento) {
            let html = `
                <div class="dados-item">
                    <span class="dados-label">Nome:</span>
                    <span class="dados-valor">${dados.nome}</span>
                </div>
                <div class="dados-item">
                    <span class="dados-label">Equipe:</span>
                    <span class="dados-valor">${dados.equipe}</span>
                </div>
                <div class="dados-item">
                    <span class="dados-label">Data:</span>
                    <span class="dados-valor">${new Date(dados.data).toLocaleDateString('pt-BR')}</span>
                </div>
                <div class="dados-item">
                    <span class="dados-label">Local:</span>
                    <span class="dados-valor">${dados.local}</span>
                </div>
                <div class="dados-item">
                    <span class="dados-label">Tipo:</span>
                    <span class="dados-valor">${mapeamento.tipoRefeicao[dados.tipoRefeicao]}</span>
                </div>
                <div class="dados-item">
                    <span class="dados-label">Motivo:</span>
                    <span class="dados-valor">${mapeamento.motivo[dados.motivo]}</span>
                </div>
                <div class="dados-item">
                    <span class="dados-label">Valor:</span>
                    <span class="dados-valor">R$ ${dados.valor}</span>
                </div>
            `;

            if (dados.observacao !== '—') {
                html += `
                    <div class="dados-item">
                        <span class="dados-label">Observação:</span>
                        <span class="dados-valor">${dados.observacao}</span>
                    </div>
                `;
            }

            resumoPedido.innerHTML = html;
            modalSucesso.classList.add('ativo');
        }

        // Função para criar confete caindo
        function criarConfete() {
            const cores = ['#667eea', '#764ba2', '#f093fb', '#4facfe', '#43e97b'];
            const quantidadeConfetes = 50;

            for (let i = 0; i < quantidadeConfetes; i++) {
                setTimeout(() => {
                    const confete = document.createElement('div');
                    confete.className = 'confete';
                    
                    const corAleatoria = cores[Math.floor(Math.random() * cores.length)];
                    confete.style.background = corAleatoria;
                    
                    const posX = Math.random() * 100;
                    confete.style.left = posX + '%';
                    confete.style.top = '-10px';
                    
                    const tamanho = Math.random() * 8 + 4;
                    confete.style.width = tamanho + 'px';
                    confete.style.height = tamanho + 'px';
                    
                    const duracao = Math.random() * 2 + 2;
                    confete.style.animation = `cair ${duracao}s linear forwards`;
                    
                    document.body.appendChild(confete);
                    
                    // Remove o elemento após a animação
                    setTimeout(() => confete.remove(), duracao * 1000);
                }, i * 30);
            }
        }

        // Botão para novo pedido
        btnNovoPedido.addEventListener('click', function() {
            form.reset();
            modalSucesso.classList.remove('ativo');
            
            // Define a data de hoje novamente
            const hoje = new Date().toISOString().split('T')[0];
            document.getElementById('data').value = hoje;
            
            // Foca no campo de nome
            document.getElementById('nome').focus();
        });

        // Botão para fechar modal
        btnFecharModal.addEventListener('click', function() {
            modalSucesso.classList.remove('ativo');
        });

        // Fecha modal ao clicar fora
        modalSucesso.addEventListener('click', function(e) {
            if (e.target === modalSucesso) {
                modalSucesso.classList.remove('ativo');
            }
        });
    </script>
</body>
</html>
