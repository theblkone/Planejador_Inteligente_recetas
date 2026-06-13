<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Saudável Diário | Dashboard</title>
    <style>
        :root {
            --primary-dark: #1b5e20; 
            --primary-color: #2e7d32;
            --secondary-color: #f4f6f5; 
            --text-color: #333;
            --card-bg: #ffffff;
            --border-color: #e0e0e0;
            --excel-color: #217346;
            --whatsapp-color: #25D366;
            --highlight: #e8f5e9;
        }

        * { box-sizing: border-box; }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--secondary-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .app-header {
            text-align: center;
            max-width: 900px;
            width: 100%;
            margin-bottom: 25px;
        }

        h1 {
            color: var(--primary-dark);
            margin: 0 0 10px 0;
            font-size: 2.2em;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .pillars {
            display: flex;
            justify-content: center;
            gap: 20px;
            color: #555;
            font-weight: 600;
            font-size: 0.95em;
            flex-wrap: wrap;
        }

        .pillars span { display: flex; align-items: center; gap: 5px; }

        .actions-bar {
            background-color: var(--card-bg);
            padding: 15px 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
            max-width: 900px;
            width: 100%;
            margin-bottom: 30px;
            border: 1px solid var(--border-color);
        }

        button {
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 15px;
            font-weight: bold;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.2s ease;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        #btnGerar { background-color: var(--primary-color); }
        #btnGerar:hover { background-color: var(--primary-dark); }
        
        #btnExportar { background-color: var(--excel-color); display: none; }
        #btnExportar:hover { background-color: #164f2f; }

        #btnWhatsApp { background-color: var(--whatsapp-color); color: #000; display: none; }
        #btnWhatsApp:hover { background-color: #20b858; }

        button:active { transform: translateY(2px); }

        .dashboard-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            max-width: 1000px;
            width: 100%;
            align-items: start;
        }

        .panel {
            background-color: var(--card-bg);
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            overflow: hidden;
            border: 1px solid var(--border-color);
            display: flex;
            flex-direction: column;
            height: 100%; /* Para alinhar os painéis */
        }

        .panel-header {
            background-color: var(--primary-dark);
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 1.2em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin: 0;
        }

        .panel-content {
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            flex-grow: 1;
        }

        .meal-item {
            border-left: 4px solid var(--primary-color);
            padding: 12px 15px;
            background-color: #fcfcfc;
            border-radius: 4px;
            border-top: 1px solid #f0f0f0;
            border-right: 1px solid #f0f0f0;
            border-bottom: 1px solid #f0f0f0;
        }

        .meal-item h3 {
            margin: 0 0 5px 0;
            color: var(--primary-color);
            font-size: 1em;
            text-transform: uppercase;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .kcal-badge {
            background-color: var(--highlight);
            color: var(--primary-dark);
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 0.85em;
            font-weight: bold;
            letter-spacing: 0;
        }

        .meal-item p { margin: 0 0 5px 0; font-weight: 600; font-size: 1.1em; color: #222;}
        .meal-item small { color: #666; font-size: 0.9em; line-height: 1.4; display: block;}

        .shopping-category { margin-bottom: 20px; }
        .shopping-category h4 {
            color: var(--primary-dark);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 5px;
            margin: 0 0 10px 0;
            font-size: 1.05em;
            text-transform: uppercase;
        }

        .shopping-list-table { width: 100%; border-collapse: collapse; list-style: none; padding: 0; margin: 0; }
        .shopping-list-table li {
            display: flex;
            justify-content: space-between;
            padding: 8px 5px;
            border-bottom: 1px solid var(--border-color);
            font-size: 0.95em;
        }
        .shopping-list-table li:nth-child(even) { background-color: #fafafa; }
        .item-name::before { content: '✓ '; color: var(--primary-color); font-weight: bold;}
        .item-price { font-weight: 600; color: var(--primary-dark); }

        .total-summary {
            text-align: right;
            font-size: 1.2em;
            font-weight: bold;
            color: var(--primary-dark);
            margin-top: auto; /* Empurra para baixo */
            padding-top: 15px;
            border-top: 2px dashed var(--border-color);
        }

        @media (max-width: 768px) {
            .dashboard-grid { grid-template-columns: 1fr; }
            .pillars { flex-direction: column; gap: 10px; align-items: center; }
        }
    </style>
</head>
<body>

    <div class="app-header">
        <h1>Planejador Inteligente</h1>
        <div class="pillars">
            <span>💰 Economia</span>
            <span>♻️ Menos Desperdício</span>
            <span>💚 Vida Saudável</span>
        </div>
    </div>

    <div class="actions-bar">
        <button id="btnGerar">Gerar Novo Cardápio</button>
        <button id="btnExportar">Baixar Planilha</button>
        <button id="btnWhatsApp">Enviar WhatsApp</button>
    </div>

    <div class="dashboard-grid">
        <div class="panel">
            <h2 class="panel-header">Cardápio do Dia</h2>
            <div id="menu-result" class="panel-content">
                </div>
        </div>

        <div class="panel">
            <h2 class="panel-header">Lista de Compras</h2>
            <div id="shopping-result" class="panel-content">
                </div>
        </div>
    </div>

    <script>
        (function() {
            // Base de 120 receitas com KCAL adicionado a cada uma
            const receitas = {
                cafe: [
                    { nome: "Ovos Mexidos com Espinafre", desc: "2 ovos mexidos com espinafre e 1 fatia de pão integral.", kcal: 240, ingredientes: ["Ovos", "Espinafre", "Pão integral"] },
                    { nome: "Mingau de Aveia com Frutas", desc: "Aveia cozida com leite desnatado, coberta com banana e chia.", kcal: 310, ingredientes: ["Aveia em flocos", "Leite", "Banana", "Sementes de chia"] },
                    { nome: "Iogurte Grego com Granola", desc: "1 potinho de iogurte grego natural, 2 colheres de granola e morangos.", kcal: 280, ingredientes: ["Iogurte grego natural", "Granola sem açúcar", "Morangos"] },
                    { nome: "Crepioca de Queijo Branco", desc: "Mistura de 1 ovo com 2 colheres de tapioca, recheada com queijo minas.", kcal: 260, ingredientes: ["Ovos", "Goma de tapioca", "Queijo minas frescal"] },
                    { nome: "Toast de Abacate", desc: "Pão integral torrado com purê de abacate temperado com limão e sal.", kcal: 290, ingredientes: ["Pão integral", "Abacate", "Limão"] },
                    { nome: "Panqueca de Banana", desc: "Massa feita com 1 ovo, 1 banana amassada e aveia, feita na frigideira.", kcal: 320, ingredientes: ["Ovos", "Banana", "Aveia em flocos"] },
                    { nome: "Vitamina de Mamão e Maçã", desc: "Mamão e maçã batidos com leite desnatado e linhaça.", kcal: 210, ingredientes: ["Mamão", "Maçã", "Leite", "Linhaça"] },
                    { nome: "Pão de Queijo de Frigideira", desc: "Mistura de tapioca, ovo e queijo ralado dourada na frigideira.", kcal: 270, ingredientes: ["Goma de tapioca", "Ovos", "Queijo ralado"] },
                    { nome: "Salada de Frutas com Quinoa", desc: "Mix de frutas da estação com flocos de quinoa crocante.", kcal: 220, ingredientes: ["Banana", "Maçã", "Morangos", "Quinoa em flocos"] },
                    { nome: "Omelete Simples", desc: "Omelete de 2 ovos com temperos naturais e um fio de azeite.", kcal: 230, ingredientes: ["Ovos", "Azeite de oliva", "Temperos naturais"] },
                    { nome: "Smoothie Verde", desc: "Abacaxi, couve, gengibre e água de coco batidos.", kcal: 180, ingredientes: ["Abacaxi", "Couve", "Gengibre", "Água de coco"] },
                    { nome: "Cuscuz Nordestino com Ovo", desc: "Porção de cuscuz de milho hidratado acompanhado de um ovo frito em fio de azeite.", kcal: 340, ingredientes: ["Flocão de milho", "Ovos", "Azeite de oliva"] },
                    { nome: "Bolo de Caneca Fit", desc: "Bolo rápido de micro-ondas feito com aveia, cacau e ovo.", kcal: 260, ingredientes: ["Aveia em flocos", "Cacau em pó", "Ovos"] },
                    { nome: "Torrada com Pasta de Amendoim", desc: "2 fatias de pão integral com pasta de amendoim e rodelas de banana.", kcal: 350, ingredientes: ["Pão integral", "Pasta de amendoim integral", "Banana"] },
                    { nome: "Tapioca com Frango Desfiado", desc: "Goma de tapioca recheada com peito de frango temperado.", kcal: 290, ingredientes: ["Goma de tapioca", "Peito de frango"] },
                    { nome: "Iogurte com Chia e Mel", desc: "Iogurte natural misturado com chia e um fio de mel.", kcal: 250, ingredientes: ["Iogurte grego natural", "Sementes de chia", "Mel"] },
                    { nome: "Waffle de Aveia", desc: "Massa de aveia e ovo feita na máquina de waffle, servida com frutas.", kcal: 270, ingredientes: ["Aveia em flocos", "Ovos", "Morangos"] },
                    { nome: "Mingau Salgado de Aveia", desc: "Aveia cozida com caldo de legumes, finalizada com ovo pochê.", kcal: 260, ingredientes: ["Aveia em flocos", "Ovos", "Temperos naturais"] },
                    { nome: "Biscoito de Arroz com Requeijão", desc: "3 biscoitos de arroz integral cobertos com requeijão light.", kcal: 150, ingredientes: ["Biscoito de arroz", "Requeijão light"] },
                    { nome: "Queijo Quente Integral", desc: "2 fatias de pão integral com queijo minas derretido na sanduicheira.", kcal: 310, ingredientes: ["Pão integral", "Queijo minas frescal"] },
                    { nome: "Frutas Vermelhas com Cottage", desc: "Potinho de queijo cottage acompanhado de amoras e morangos.", kcal: 210, ingredientes: ["Queijo cottage", "Morangos", "Amoras"] },
                    { nome: "Creme de Abacate Doce", desc: "Abacate amassado com cacau em pó e adoçante natural.", kcal: 280, ingredientes: ["Abacate", "Cacau em pó"] },
                    { nome: "Pão Sírio com Homus", desc: "Pão sírio integral tostado servido com pasta de grão de bico.", kcal: 300, ingredientes: ["Pão sírio integral", "Homus"] },
                    { nome: "Ovos Cozidos com Azeite", desc: "2 ovos cozidos cortados ao meio com azeite e orégano.", kcal: 220, ingredientes: ["Ovos", "Azeite de oliva"] },
                    { nome: "Panqueca de Espinafre", desc: "Massa verde feita com espinafre e ovo, recheada com ricota.", kcal: 240, ingredientes: ["Espinafre", "Ovos", "Creme de ricota"] },
                    { nome: "Vitamina de Morango e Chia", desc: "Morangos batidos com leite vegetal e sementes de chia.", kcal: 190, ingredientes: ["Morangos", "Leite", "Sementes de chia"] },
                    { nome: "Misto Quente Fit", desc: "Pão integral com peito de peru e uma fatia fina de queijo.", kcal: 280, ingredientes: ["Pão integral", "Peito de peru fatiado", "Queijo minas frescal"] },
                    { nome: "Tapioca com Ovo Mexido", desc: "Clássica tapioca com recheio de um ovo mexido úmido.", kcal: 270, ingredientes: ["Goma de tapioca", "Ovos"] },
                    { nome: "Leite com Cacau e Torradas", desc: "Xícara de leite quente com cacau 100% e torradas integrais.", kcal: 240, ingredientes: ["Leite", "Cacau em pó", "Torradas integrais"] },
                    { nome: "Mingau de Quinoa", desc: "Quinoa em flocos cozida com leite de amêndoas e canela.", kcal: 290, ingredientes: ["Quinoa em flocos", "Leite", "Canela em pó"] }
                ],
                almoco: [
                    { nome: "Salada de Quinoa com Frango", desc: "Frango grelhado, quinoa cozida, tomate cereja, pepino e azeite.", kcal: 420, ingredientes: ["Peito de frango", "Quinoa", "Tomate cereja", "Pepino", "Azeite de oliva"] },
                    { nome: "Filé de Peixe com Legumes", desc: "Pescada assada com brócolis, cenoura e batata doce.", kcal: 380, ingredientes: ["Filé de peixe", "Brócolis", "Cenoura", "Batata doce"] },
                    { nome: "Wrap de Peito de Peru", desc: "Rap10 integral com peito de peru, alface, tomate e ricota.", kcal: 350, ingredientes: ["Massa de wrap integral", "Peito de peru fatiado", "Alface", "Tomate", "Creme de ricota"] },
                    { nome: "Macarrão Integral com Patinho", desc: "Massa integral com molho de tomate e carne moída magra.", kcal: 480, ingredientes: ["Macarrão integral", "Molho de tomate", "Carne moída (patinho)"] },
                    { nome: "Milanesa de Forno com Purê", desc: "Bife magro empanado na aveia e assado, com purê de abóbora.", kcal: 510, ingredientes: ["Bife magro", "Aveia em flocos", "Abóbora", "Ovos"] },
                    { nome: "Estrogonofe Fit de Frango", desc: "Frango com molho de tomate e iogurte natural, acompanhado de arroz integral.", kcal: 490, ingredientes: ["Peito de frango", "Molho de tomate", "Iogurte grego natural", "Arroz integral"] },
                    { nome: "Bife Acebolado com Arroz e Feijão", desc: "Almoço clássico: bife magro com cebola, arroz integral e feijão.", kcal: 550, ingredientes: ["Bife magro", "Cebola", "Arroz integral", "Feijão"] },
                    { nome: "Escondidinho de Batata Doce", desc: "Purê de batata doce recheado com frango desfiado temperado.", kcal: 450, ingredientes: ["Batata doce", "Peito de frango"] },
                    { nome: "Salmão Grelhado com Aspargos", desc: "Posta de salmão feita no azeite com aspargos salteados.", kcal: 470, ingredientes: ["Salmão", "Aspargos", "Azeite de oliva"] },
                    { nome: "Panqueca de Carne Moída", desc: "Panqueca de farinha integral recheada com patinho moído.", kcal: 440, ingredientes: ["Farinha integral", "Ovos", "Carne moída (patinho)", "Molho de tomate"] },
                    { nome: "Berinjela à Parmegiana Fit", desc: "Fatias de berinjela assadas com molho de tomate e um pouco de queijo.", kcal: 320, ingredientes: ["Berinjela", "Molho de tomate", "Queijo ralado"] },
                    { nome: "Salada de Grão de Bico", desc: "Grão de bico cozido com cebola roxa, tomate, pepino e atum.", kcal: 410, ingredientes: ["Grão de bico", "Cebola", "Tomate", "Pepino", "Atum em lata"] },
                    { nome: "Frango ao Curry com Legumes", desc: "Cubos de frango ao curry acompanhados de cenoura e couve-flor.", kcal: 430, ingredientes: ["Peito de frango", "Cenoura", "Couve-flor", "Curry em pó"] },
                    { nome: "Iscas de Carne com Brócolis", desc: "Tirinhas de carne salteadas na panela wok com flores de brócolis.", kcal: 460, ingredientes: ["Bife magro", "Brócolis", "Molho shoyu light"] },
                    { nome: "Nhoque de Batata Doce", desc: "Nhoque caseiro servido com molho sugo natural.", kcal: 390, ingredientes: ["Batata doce", "Farinha integral", "Molho de tomate"] },
                    { nome: "Peixe Assado com Batatas", desc: "Filé branco assado no papel alumínio com rodelas de batata e cebola.", kcal: 400, ingredientes: ["Filé de peixe", "Batata inglesa", "Cebola"] },
                    { nome: "Picadinho com Cenoura", desc: "Carne picada cozida no caldo com cubinhos de cenoura.", kcal: 430, ingredientes: ["Bife magro", "Cenoura", "Temperos naturais"] },
                    { nome: "Sobrecoxa Assada com Alecrim", desc: "Sobrecoxa sem pele assada com ramos de alecrim e tomates.", kcal: 450, ingredientes: ["Sobrecoxa de frango", "Alecrim", "Tomate"] },
                    { nome: "Risoto de Quinoa com Cogumelos", desc: "Quinoa preparada estilo risoto com cogumelos frescos.", kcal: 410, ingredientes: ["Quinoa", "Cogumelos", "Cebola"] },
                    { nome: "Lasanha de Abobrinha", desc: "Lâminas de abobrinha intercaladas com carne moída e queijo.", kcal: 380, ingredientes: ["Abobrinha", "Carne moída (patinho)", "Queijo ralado"] },
                    { nome: "Fricassê de Frango Fit", desc: "Frango com creme de milho feito com leite desnatado.", kcal: 460, ingredientes: ["Peito de frango", "Milho verde", "Leite"] },
                    { nome: "Carne Assada com Mandioca", desc: "Pedaço de lagarto assado fatiado, acompanhado de mandioca cozida.", kcal: 490, ingredientes: ["Carne de panela", "Mandioca"] },
                    { nome: "Frango Xadrez Fit", desc: "Frango em cubos com pimentão, cebola e amendoim.", kcal: 440, ingredientes: ["Peito de frango", "Pimentão", "Cebola", "Amendoim"] },
                    { nome: "Omelete Recheado no Almoço", desc: "Omelete grande recheado com espinafre e carne moída.", kcal: 410, ingredientes: ["Ovos", "Espinafre", "Carne moída (patinho)"] },
                    { nome: "Salada de Feijão Fradinho", desc: "Feijão fradinho misturado com pimentão, cebola, azeite e vinagre.", kcal: 370, ingredientes: ["Feijão fradinho", "Pimentão", "Cebola", "Azeite de oliva"] },
                    { nome: "Carne de Panela com Legumes", desc: "Cozido de carne com chuchu, cenoura e batata.", kcal: 460, ingredientes: ["Carne de panela", "Chuchu", "Cenoura", "Batata inglesa"] },
                    { nome: "Hambúrguer de Patinho no Prato", desc: "Hambúrguer caseiro grelhado servido com farta salada verde.", kcal: 380, ingredientes: ["Carne moída (patinho)", "Alface", "Tomate"] },
                    { nome: "Arroz de Forno Saudável", desc: "Sobras de arroz integral misturadas com frango, ervilha e cenoura.", kcal: 440, ingredientes: ["Arroz integral", "Peito de frango", "Ervilha", "Cenoura"] },
                    { nome: "Moqueca Baiana Light", desc: "Moqueca de peixe feita com leite de coco light e azeite doce.", kcal: 410, ingredientes: ["Filé de peixe", "Leite de coco light", "Pimentão", "Tomate"] },
                    { nome: "Charuto de Repolho", desc: "Folhas de repolho recheadas com arroz e carne moída cozidas no tomate.", kcal: 390, ingredientes: ["Repolho", "Arroz integral", "Carne moída (patinho)", "Molho de tomate"] }
                ],
                lanche: [
                    { nome: "Mix de Castanhas", desc: "Um punhado de nozes, castanha do pará e amêndoas.", kcal: 210, ingredientes: ["Nozes", "Castanha do Pará", "Amêndoas"] },
                    { nome: "Maçã com Pasta de Amendoim", desc: "Maçã cortada com 1 colher de sopa de pasta de amendoim.", kcal: 230, ingredientes: ["Maçã", "Pasta de amendoim integral"] },
                    { nome: "Vitamina de Abacate", desc: "Meio abacate batido com leite e um fio de mel.", kcal: 260, ingredientes: ["Abacate", "Leite", "Mel"] },
                    { nome: "Cenoura com Homus", desc: "Palitos de cenoura fresca mergulhados em pasta de grão de bico.", kcal: 180, ingredientes: ["Cenoura", "Homus"] },
                    { nome: "Pipoca de Panela", desc: "Pipoca estourada na panela com apenas um fio de óleo ou azeite.", kcal: 150, ingredientes: ["Milho de pipoca", "Azeite de oliva"] },
                    { nome: "Mate com Tostadas Integrais", desc: "Infusão de erva mate acompanhada de duas torradas integrais.", kcal: 120, ingredientes: ["Erva mate", "Torradas integrais"] },
                    { nome: "Ovo Cozido Temperado", desc: "1 ovo cozido com pitada de sal e orégano.", kcal: 78, ingredientes: ["Ovos", "Temperos naturais"] },
                    { nome: "Smoothie de Morango", desc: "Morangos congelados batidos com iogurte natural.", kcal: 160, ingredientes: ["Morangos", "Iogurte grego natural"] },
                    { nome: "Banana Amassada com Aveia", desc: "Praticidade: uma banana amassada no prato salpicada com aveia.", kcal: 190, ingredientes: ["Banana", "Aveia em flocos"] },
                    { nome: "Tomate Cereja com Queijo", desc: "Espetinhos de tomate cereja com cubos de queijo branco.", kcal: 170, ingredientes: ["Tomate cereja", "Queijo minas frescal"] },
                    { nome: "Edamame Cozido", desc: "Vagem de soja cozida no vapor com uma pitada de sal grosso.", kcal: 120, ingredientes: ["Edamame"] },
                    { nome: "Bolinhas de Energia", desc: "Bolinhas cruas de tâmara triturada com cacau e coco.", kcal: 240, ingredientes: ["Tâmaras", "Cacau em pó", "Coco ralado"] },
                    { nome: "Chips de Batata Doce", desc: "Rodelas finas de batata doce assadas no forno até ficarem crocantes.", kcal: 180, ingredientes: ["Batata doce", "Azeite de oliva"] },
                    { nome: "Rolinhos de Peito de Peru", desc: "Fatias de peito de peru enroladas com creme de ricota no centro.", kcal: 150, ingredientes: ["Peito de peru fatiado", "Creme de ricota"] },
                    { nome: "Pudim de Chia", desc: "Chia hidratada no leite de coco de um dia para o outro, com frutas.", kcal: 210, ingredientes: ["Sementes de chia", "Leite de coco light", "Morangos"] },
                    { nome: "Cubos de Coco Fresco", desc: "Porção de coco fresco natural cortado em pedaços.", kcal: 220, ingredientes: ["Coco fresco"] },
                    { nome: "Iogurte com Mirtilos", desc: "Iogurte natural misturado com mirtilos frescos.", kcal: 140, ingredientes: ["Iogurte grego natural", "Mirtilos"] },
                    { nome: "Pera com Nozes", desc: "Uma pera suculenta fatiada, acompanhada de algumas nozes.", kcal: 190, ingredientes: ["Pera", "Nozes"] },
                    { nome: "Maçã Assada com Canela", desc: "Maçã sem miolo assada no micro-ondas com canela em pó.", kcal: 110, ingredientes: ["Maçã", "Canela em pó"] },
                    { nome: "Queijo Cottage com Mel", desc: "Pequena taça de queijo cottage com um fio de mel e chia.", kcal: 170, ingredientes: ["Queijo cottage", "Mel", "Sementes de chia"] },
                    { nome: "Biscoito de Arroz com Guacamole", desc: "Biscoitos de arroz cobertos com purê de abacate temperado.", kcal: 220, ingredientes: ["Biscoito de arroz", "Abacate", "Tomate", "Cebola"] },
                    { nome: "Crepioca Doce", desc: "Massa de crepioca misturada com cacau, sem recheio.", kcal: 200, ingredientes: ["Goma de tapioca", "Ovos", "Cacau em pó"] },
                    { nome: "Alfajor de Aveia Fit", desc: "Duas bolachas caseiras de aveia unidas por um pouco de pasta de amendoim.", kcal: 250, ingredientes: ["Aveia em flocos", "Pasta de amendoim integral", "Ovos"] },
                    { nome: "Palitos de Pepino com Limão", desc: "Pepino cortado em tiras com sal e suco de limão.", kcal: 30, ingredientes: ["Pepino", "Limão"] },
                    { nome: "Pão de Queijo Fit (Lanche)", desc: "1 unidade de pão de queijo funcional de batata doce e polvilho.", kcal: 160, ingredientes: ["Batata doce", "Polvilho azedo", "Queijo ralado"] },
                    { nome: "Frutas Secas (Damasco e Uva)", desc: "Pequena porção de damascos secos e uvas passas.", kcal: 180, ingredientes: ["Damasco seco", "Uva passa"] },
                    { nome: "Mingau Frio (Overnight Oats)", desc: "Aveia embebida no leite de véspera, consumida gelada.", kcal: 210, ingredientes: ["Aveia em flocos", "Leite"] },
                    { nome: "Gelatina Sem Açúcar", desc: "Duas taças de gelatina diet preparada em casa.", kcal: 15, ingredientes: ["Gelatina diet"] },
                    { nome: "Açaí Zero Xarope", desc: "Polpa de açaí puro batido com meia banana para adoçar.", kcal: 240, ingredientes: ["Polpa de açaí", "Banana"] },
                    { nome: "Snack de Grão de Bico Assado", desc: "Grão de bico assado com páprica e azeite até ficar crocante.", kcal: 200, ingredientes: ["Grão de bico", "Azeite de oliva", "Páprica doce"] }
                ],
                jantar: [
                    { nome: "Sopa de Legumes com Frango", desc: "Sopa caseira de abóbora, chuchu, cenoura e frango.", kcal: 280, ingredientes: ["Abóbora", "Chuchu", "Cenoura", "Peito de frango"] },
                    { nome: "Empanadas Tucumanas Assadas", desc: "Clássicas empanadas al horno: carne cortada a cuchillo, huevo, comino y pimentón.", kcal: 450, ingredientes: ["Massa para empanadas", "Carne (para cortar na faca)", "Ovos", "Cebola", "Cominho", "Páprica doce"] },
                    { nome: "Salada Completa com Atum", desc: "Folhas, tomate, pepino, cenoura e atum.", kcal: 260, ingredientes: ["Mix de folhas verdes", "Tomate", "Pepino", "Cenoura", "Atum em lata"] },
                    { nome: "Abobrinha Recheada", desc: "Abobrinha recheada com carne moída gratinada.", kcal: 310, ingredientes: ["Abobrinha", "Carne moída (patinho)", "Queijo ralado"] },
                    { nome: "Omelete de Forno", desc: "Omelete espesso assado com tomate e ervilhas.", kcal: 290, ingredientes: ["Ovos", "Tomate", "Ervilha"] },
                    { nome: "Caldo Verde Fit", desc: "Caldo espesso de couve com batata doce em vez de batata inglesa.", kcal: 320, ingredientes: ["Couve", "Batata doce", "Cebola"] },
                    { nome: "Sopa de Abóbora com Gengibre", desc: "Creme aveludado de abóbora cozida e processada com gengibre.", kcal: 210, ingredientes: ["Abóbora", "Gengibre"] },
                    { nome: "Pizza de Couve-Flor", desc: "Massa feita de couve-flor triturada, coberta com tomate e queijo.", kcal: 350, ingredientes: ["Couve-flor", "Molho de tomate", "Queijo minas frescal"] },
                    { nome: "Filé de Frango com Salada Caesar Fit", desc: "Frango grelhado sobre alface americana com molho de iogurte.", kcal: 380, ingredientes: ["Peito de frango", "Alface", "Iogurte grego natural"] },
                    { nome: "Creme de Espinafre Saudável", desc: "Folhas de espinafre cozidas em creme de ricota.", kcal: 260, ingredientes: ["Espinafre", "Creme de ricota", "Alho"] },
                    { nome: "Torta de Frango de Liquidificador", desc: "Torta de massa leve (aveia) com frango desfiado, assada.", kcal: 410, ingredientes: ["Aveia em flocos", "Peito de frango", "Ovos"] },
                    { nome: "Espaguete de Abobrinha", desc: "Fios de abobrinha salteados com molho bolonhesa magro.", kcal: 270, ingredientes: ["Abobrinha", "Carne moída (patinho)", "Molho de tomate"] },
                    { nome: "Salada Caprese", desc: "Rodelas de tomate intercaladas com queijo branco e manjericão.", kcal: 320, ingredientes: ["Tomate", "Queijo minas frescal", "Azeite de oliva"] },
                    { nome: "Caldo de Feijão", desc: "Feijão batido quente, consumido em xícara ou cumbuca.", kcal: 300, ingredientes: ["Feijão", "Alho", "Temperos naturais"] },
                    { nome: "Salada Morna de Grão de Bico", desc: "Grão de bico refogado levemente com tomate e espinafre.", kcal: 340, ingredientes: ["Grão de bico", "Tomate", "Espinafre"] },
                    { nome: "Souflé de Queijo Leve", desc: "Souflé assado feito com claras em neve e queijo branco ralado.", kcal: 290, ingredientes: ["Ovos", "Queijo minas frescal", "Leite"] },
                    { nome: "Berinjela Grelhada com Tomate", desc: "Fatias grossas de berinjela feitas na chapa com rodelas de tomate.", kcal: 230, ingredientes: ["Berinjela", "Tomate", "Azeite de oliva"] },
                    { nome: "Atum com Batata Doce Amassada", desc: "Lata de atum misturada com purê rústico de batata doce.", kcal: 360, ingredientes: ["Atum em lata", "Batata doce"] },
                    { nome: "Salpicão de Frango Fit", desc: "Frango desfiado com cenoura, milho e iogurte natural no lugar da maionese.", kcal: 390, ingredientes: ["Peito de frango", "Cenoura", "Milho verde", "Iogurte grego natural"] },
                    { nome: "Canja de Galinha Integral", desc: "Sopa nutritiva de frango, cenoura e arroz integral.", kcal: 330, ingredientes: ["Peito de frango", "Arroz integral", "Cenoura"] },
                    { nome: "Ovos Pochê com Espinafre", desc: "Ovos cozidos em água fervente sobre uma cama de espinafre refogado.", kcal: 240, ingredientes: ["Ovos", "Espinafre"] },
                    { nome: "Sopa de Cebola Leve", desc: "Cebolas douradas e cozidas no caldo de carne magro.", kcal: 180, ingredientes: ["Cebola", "Temperos naturais"] },
                    { nome: "Wrap de Frango Light", desc: "Frango grelhado enrolado na massa fina com alface.", kcal: 340, ingredientes: ["Massa de wrap integral", "Peito de frango", "Alface"] },
                    { nome: "Frittata de Legumes", desc: "Ovos batidos assados na frigideira com sobras de legumes do almoço.", kcal: 280, ingredientes: ["Ovos", "Cenoura", "Brócolis"] },
                    { nome: "Hambúrguer de Lentilha", desc: "Disco vegetariano de lentilha cozida e grelhada, acompanhado de salada.", kcal: 350, ingredientes: ["Lentilha", "Cebola", "Tomate"] },
                    { nome: "Cogumelos Salteados no Azeite", desc: "Shitake e shimeji feitos rapidamente na frigideira.", kcal: 200, ingredientes: ["Cogumelos", "Azeite de oliva", "Molho shoyu light"] },
                    { nome: "Choripán Fit (Desconstruído)", desc: "Linguiça de frango magra assada, servida com vinagrete e pão integral.", kcal: 420, ingredientes: ["Linguiça de frango", "Pão integral", "Tomate", "Cebola"] },
                    { nome: "Cuscuz Marroquino com Vegetais", desc: "Sêmola hidratada misturada com cenoura ralada e pimentão.", kcal: 290, ingredientes: ["Cuscuz marroquino", "Cenoura", "Pimentão"] },
                    { nome: "Locro Leve (Versão Fit)", desc: "Ensopado de milho branco e abóbora com pedaços de carne magra.", kcal: 400, ingredientes: ["Milho branco", "Abóbora", "Bife magro"] },
                    { nome: "Tomates Recheados", desc: "Tomates inteiros esvaziados e recheados com atum e ricota, assados.", kcal: 250, ingredientes: ["Tomate", "Atum em lata", "Creme de ricota"] }
                ]
            };

            const precosEstimados = {
                "Ovos": 12.50, "Espinafre": 4.00, "Pão integral": 8.50, "Aveia em flocos": 6.00,
                "Leite": 5.50, "Banana": 4.50, "Sementes de chia": 10.00, "Iogurte grego natural": 14.00,
                "Granola sem açúcar": 16.00, "Morangos": 9.00, "Goma de tapioca": 7.50, "Queijo minas frescal": 18.00,
                "Peito de frango": 22.00, "Quinoa": 15.00, "Tomate cereja": 6.50, "Pepino": 3.50, "Azeite de oliva": 28.00,
                "Filé de peixe": 30.00, "Brócolis": 6.00, "Cenoura": 4.00, "Batata doce": 5.00,
                "Massa de wrap integral": 9.50, "Peito de peru fatiado": 11.00, "Alface": 3.00, "Tomate": 5.00,
                "Creme de ricota": 8.00, "Macarrão integral": 7.00, "Molho de tomate": 5.50, "Carne moída (patinho)": 38.00,
                "Nozes": 20.00, "Castanha do Pará": 25.00, "Amêndoas": 24.00, "Maçã": 7.00, "Pasta de amendoim integral": 17.00,
                "Abacate": 6.00, "Mel": 20.00, "Homus": 14.00, "Abóbora": 4.50, "Chuchu": 3.00,
                "Massa para empanadas": 12.00, "Carne (para cortar na faca)": 42.00, "Cebola": 4.00, "Cominho": 3.00, "Páprica doce": 3.50,
                "Mix de folhas verdes": 6.00, "Atum em lata": 9.00, "Abobrinha": 4.00, "Queijo ralado": 7.50,
                "Bife magro": 40.00, "Arroz integral": 6.50, "Feijão": 8.00, "Mandioca": 5.00, "Erva mate": 15.00, "Cacau em pó": 12.00
            };

            const categoriasIngredientes = {
                "Espinafre": "Hortifruti", "Banana": "Hortifruti", "Morangos": "Hortifruti", "Tomate cereja": "Hortifruti",
                "Pepino": "Hortifruti", "Brócolis": "Hortifruti", "Cenoura": "Hortifruti", "Batata doce": "Hortifruti",
                "Alface": "Hortifruti", "Tomate": "Hortifruti", "Maçã": "Hortifruti", "Abacate": "Hortifruti",
                "Abóbora": "Hortifruti", "Chuchu": "Hortifruti", "Cebola": "Hortifruti", "Mix de folhas verdes": "Hortifruti",
                "Abobrinha": "Hortifruti", "Limão": "Hortifruti", "Mamão": "Hortifruti", "Amoras": "Hortifruti",
                "Couve": "Hortifruti", "Abacaxi": "Hortifruti", "Gengibre": "Hortifruti", "Mirtilos": "Hortifruti",
                "Pera": "Hortifruti", "Coco fresco": "Hortifruti", "Mandioca": "Hortifruti", "Berinjela": "Hortifruti",
                "Pimentão": "Hortifruti", "Alho": "Hortifruti", "Cogumelos": "Hortifruti", "Repolho": "Hortifruti",
                
                "Ovos": "Laticínios e Frios", "Leite": "Laticínios e Frios", "Iogurte grego natural": "Laticínios e Frios",
                "Queijo minas frescal": "Laticínios e Frios", "Peito de peru fatiado": "Laticínios e Frios",
                "Creme de ricota": "Laticínios e Frios", "Queijo ralado": "Laticínios e Frios", "Queijo cottage": "Laticínios e Frios",
                "Requeijão light": "Laticínios e Frios",
                
                "Peito de frango": "Açougue e Peixaria", "Filé de peixe": "Açougue e Peixaria", 
                "Carne moída (patinho)": "Açougue e Peixaria", "Carne (para cortar na faca)": "Açougue e Peixaria",
                "Bife magro": "Açougue e Peixaria", "Salmão": "Açougue e Peixaria", "Sobrecoxa de frango": "Açougue e Peixaria",
                "Carne de panela": "Açougue e Peixaria", "Linguiça de frango": "Açougue e Peixaria",
                
                "Pão integral": "Mercearia", "Aveia em flocos": "Mercearia", "Sementes de chia": "Mercearia",
                "Granola sem açúcar": "Mercearia", "Goma de tapioca": "Mercearia", "Quinoa": "Mercearia",
                "Azeite de oliva": "Mercearia", "Massa de wrap integral": "Mercearia", "Macarrão integral": "Mercearia",
                "Molho de tomate": "Mercearia", "Nozes": "Mercearia", "Castanha do Pará": "Mercearia",
                "Amêndoas": "Mercearia", "Pasta de amendoim integral": "Mercearia", "Mel": "Mercearia",
                "Homus": "Mercearia", "Massa para empanadas": "Mercearia", "Cominho": "Mercearia",
                "Páprica doce": "Mercearia", "Atum em lata": "Mercearia", "Linhaça": "Mercearia", 
                "Quinoa em flocos": "Mercearia", "Cacau em pó": "Mercearia", "Flocão de milho": "Mercearia",
                "Água de coco": "Mercearia", "Pão sírio integral": "Mercearia", "Torradas integrais": "Mercearia",
                "Biscoito de arroz": "Mercearia", "Arroz integral": "Mercearia", "Feijão": "Mercearia",
                "Molho shoyu light": "Mercearia", "Farinha integral": "Mercearia", "Curry em pó": "Mercearia",
                "Alecrim": "Mercearia", "Milho verde": "Mercearia", "Amendoim": "Mercearia", "Feijão fradinho": "Mercearia",
                "Milho de pipoca": "Mercearia", "Erva mate": "Mercearia", "Edamame": "Mercearia", "Tâmaras": "Mercearia",
                "Coco ralado": "Mercearia", "Canela em pó": "Mercearia", "Damasco seco": "Mercearia", 
                "Uva passa": "Mercearia", "Gelatina diet": "Mercearia", "Polpa de açaí": "Mercearia",
                "Ervilha": "Mercearia", "Lentilha": "Mercearia", "Cuscuz marroquino": "Mercearia", "Milho branco": "Mercearia",
                "Temperos naturais": "Mercearia"
            };

            let menuAtual = [];
            let listaAgrupada = {};

            function sortear(array) {
                return array[Math.floor(Math.random() * array.length)];
            }

            function gerarMenu() {
                const menuContainer = document.getElementById('menu-result');
                const shoppingContainer = document.getElementById('shopping-result');
                const btnExportar = document.getElementById('btnExportar');
                const btnWhatsApp = document.getElementById('btnWhatsApp');
                
                if (!menuContainer || !shoppingContainer) return;

                menuContainer.innerHTML = ''; 
                shoppingContainer.innerHTML = ''; 

                menuAtual = [
                    { tipo: "Café da Manhã", ...sortear(receitas.cafe) },
                    { tipo: "Almoço", ...sortear(receitas.almoco) },
                    { tipo: "Lanche da Tarde", ...sortear(receitas.lanche) },
                    { tipo: "Jantar", ...sortear(receitas.jantar) }
                ];

                let todosIngredientes = [];
                let kcalTotalDoDia = 0;

                // Renderiza Cardápio
                menuAtual.forEach(refeicao => {
                    kcalTotalDoDia += refeicao.kcal;
                    
                    const card = document.createElement('div');
                    card.className = 'meal-item';
                    card.innerHTML = `
                        <h3>${refeicao.tipo} <span class="kcal-badge">${refeicao.kcal} kcal</span></h3>
                        <p>${refeicao.nome}</p>
                        <small>${refeicao.desc}</small>
                    `;
                    menuContainer.appendChild(card);

                    if (refeicao.ingredientes) {
                        todosIngredientes = todosIngredientes.concat(refeicao.ingredientes);
                    }
                });

                // Adiciona o Total de Calorias no fim da coluna Cardápio
                const totalKcalDiv = document.createElement('div');
                totalKcalDiv.className = 'total-summary';
                totalKcalDiv.innerHTML = `Total Diário: ${kcalTotalDoDia} kcal`;
                menuContainer.appendChild(totalKcalDiv);

                const ingredientesAtuais = [...new Set(todosIngredientes)].sort();

                listaAgrupada = {
                    "Hortifruti": [],
                    "Açougue e Peixaria": [],
                    "Laticínios e Frios": [],
                    "Mercearia": [],
                    "Outros": []
                };

                ingredientesAtuais.forEach(item => {
                    const categoria = categoriasIngredientes[item] || "Outros";
                    listaAgrupada[categoria].push(item);
                });

                if (ingredientesAtuais.length > 0) {
                    btnExportar.style.display = 'inline-block';
                    btnWhatsApp.style.display = 'inline-block'; 
                    
                    let custoTotal = 0;

                    Object.keys(listaAgrupada).forEach(categoria => {
                        if (listaAgrupada[categoria].length > 0) {
                            const catDiv = document.createElement('div');
                            catDiv.className = 'shopping-category';
                            
                            let listHTML = `<h4>${categoria}</h4><ul class="shopping-list-table">`;
                            
                            listaAgrupada[categoria].forEach(ingrediente => {
                                const preco = precosEstimados[ingrediente] || 5.00;
                                custoTotal += preco;
                                listHTML += `
                                    <li>
                                        <span class="item-name">${ingrediente}</span>
                                        <span class="item-price">R$ ${preco.toFixed(2).replace('.', ',')}</span>
                                    </li>`;
                            });
                            
                            listHTML += '</ul>';
                            catDiv.innerHTML = listHTML;
                            shoppingContainer.appendChild(catDiv);
                        }
                    });

                    // Adiciona o Total de Preços no fim da coluna Compras
                    const totalCostDiv = document.createElement('div');
                    totalCostDiv.className = 'total-summary';
                    totalCostDiv.innerHTML = `Custo Estimado: R$ ${custoTotal.toFixed(2).replace('.', ',')}`;
                    shoppingContainer.appendChild(totalCostDiv);
                }
            }

            function exportarParaExcel() {
                if (menuAtual.length === 0) return;
                let conteudoCSV = "\uFEFF"; 

                let kcalTotalDoDia = 0;

                conteudoCSV += "--- MENU DO DIA ---\nRefeição;Prato;Calorias;Descrição\n";
                menuAtual.forEach(ref => {
                    kcalTotalDoDia += ref.kcal;
                    conteudoCSV += `"${ref.tipo}";"${ref.nome}";"${ref.kcal} kcal";"${ref.desc}"\n`;
                });
                
                conteudoCSV += `\n"";"TOTAL DIÁRIO";"${kcalTotalDoDia} kcal"\n\n`;

                conteudoCSV += "--- LISTA DE COMPRAS ---\nCategoria;Ingrediente;Preço Estimado\n";
                
                let custoTotal = 0;
                Object.keys(listaAgrupada).forEach(categoria => {
                    listaAgrupada[categoria].forEach(item => {
                        const preco = precosEstimados[item] || 5.00;
                        custoTotal += preco;
                        conteudoCSV += `"${categoria}";"${item}";"R$ ${preco.toFixed(2).replace('.', ',')}"\n`;
                    });
                });
                conteudoCSV += `\n"";"CUSTO TOTAL ESTIMADO";"R$ ${custoTotal.toFixed(2).replace('.', ',')}"\n`;

                const blob = new Blob([conteudoCSV], { type: 'text/csv;charset=utf-8;' });
                const link = document.createElement("a");
                const url = URL.createObjectURL(blob);
                link.setAttribute("href", url);
                link.setAttribute("download", "menu_e_compras.csv");
                link.style.visibility = 'hidden';
                document.body.appendChild(link);
                link.click();
                document.body.removeChild(link);
            }

            function enviarPorWhatsApp() {
                if (menuAtual.length === 0) return;
                
                let corpo = "*MENU DE HOJE:*\n\n";
                let kcalTotalDoDia = 0;
                
                menuAtual.forEach(ref => { 
                    kcalTotalDoDia += ref.kcal;
                    corpo += `*${ref.tipo} (${ref.kcal} kcal):* ${ref.nome}\n`; 
                });
                
                corpo += `\n*Total Calórico do Dia:* ${kcalTotalDoDia} kcal\n`;

                corpo += "\n*LISTA DE COMPRAS:*\n";
                let custoTotal = 0;
                
                Object.keys(listaAgrupada).forEach(categoria => {
                    if (listaAgrupada[categoria].length > 0) {
                        corpo += `\n*[ ${categoria.toUpperCase()} ]*\n`;
                        listaAgrupada[categoria].forEach(item => {
                            const preco = precosEstimados[item] || 5.00;
                            custoTotal += preco;
                            corpo += `• ${item} (R$ ${preco.toFixed(2).replace('.', ',')})\n`;
                        });
                    }
                });
                corpo += `\n*Custo Total Estimado:* R$ ${custoTotal.toFixed(2).replace('.', ',')}`;
                
                const linkWhatsApp = `https://wa.me/?text=${encodeURIComponent(corpo)}`;
                window.open(linkWhatsApp, '_blank');
            }

            const btnGerar = document.getElementById('btnGerar');
            if (btnGerar) btnGerar.addEventListener('click', gerarMenu);
            const btnExportar = document.getElementById('btnExportar');
            if (btnExportar) btnExportar.addEventListener('click', exportarParaExcel);
            const btnWhatsApp = document.getElementById('btnWhatsApp');
            if (btnWhatsApp) btnWhatsApp.addEventListener('click', enviarPorWhatsApp);

            gerarMenu();
        })();
    </script>
</body>
</html>
