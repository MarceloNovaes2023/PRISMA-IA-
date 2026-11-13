<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRISMA IA - Dashboard de Vendas</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root{--bg:#0a0e17;--bg-card:#111827;--bg-header:#0d1117;--text:#e5e7eb;--text-muted:#6b7280;--accent:#00d4aa;--accent-hover:#00bb8e;--border:#1f2937;--card-shadow:0 4px 20px rgba(0,0,0,0.4);--radius:12px;--success:#10b981;--warning:#f59e0b;--danger:#ef4444;--info:#3b82f6}
        *{margin:0;padding:0;box-sizing:border-box}
        body{font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);line-height:1.6}
        .container{max-width:1400px;margin:0 auto;padding:1.5rem}
        header{background:var(--bg-header);border-radius:var(--radius);padding:1.5rem 2rem;margin-bottom:1.5rem;border:1px solid var(--border)}
        .header-inner{display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:1rem}
        .logo{display:flex;align-items:center;gap:.8rem}
        .logo-icon{width:44px;height:44px;background:linear-gradient(135deg,var(--accent),#00f5c4);border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:1.3rem;font-weight:bold;color:var(--bg);box-shadow:0 4px 15px rgba(0,212,170,.3)}
        .logo-text{font-size:1.5rem;font-weight:700;color:var(--text)}.logo-text span{color:var(--accent)}
        .filters{background:var(--bg-card);border-radius:var(--radius);padding:1rem 1.5rem;margin-bottom:1.5rem;border:1px solid var(--border);display:flex;gap:1rem;align-items:center;flex-wrap:wrap}
        .filters label{font-size:.8rem;text-transform:uppercase;letter-spacing:.5px;color:var(--text-muted);min-width:80px}
        .filters select{background:var(--bg);border:1px solid var(--border);color:var(--text);padding:.6rem 1rem;border-radius:6px;font-size:.9rem;min-width:150px}
        .filters select:focus{outline:none;border-color:var(--accent)}
        .grid-2{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:1.5rem;margin-bottom:1.5rem}
        .grid-3{display:grid;grid-template-columns:repeat(auto-fit,minmax(350px,1fr));gap:1.5rem;margin-bottom:1.5rem}
        .grid-4{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.5rem;margin-bottom:1.5rem}
        .section-title{font-size:1.1rem;color:var(--text-muted);text-transform:uppercase;letter-spacing:.5px;margin-bottom:1rem;padding-bottom:.5rem;border-bottom:1px solid var(--border)}
        .metric-card{background:var(--bg-card);border-radius:var(--radius);padding:1.5rem;border:1px solid var(--border);box-shadow:var(--card-shadow);transition:transform .2s}
        .metric-card:hover{transform:translateY(-2px)}
        .metric-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:.8rem}
        .metric-title{font-size:.8rem;text-transform:uppercase;letter-spacing:1px;color:var(--text-muted)}
        .metric-value{font-size:2rem;font-weight:700;color:var(--text)}
        .metric-trend{display:flex;align-items:center;gap:.4rem;font-size:.85rem;margin-top:.5rem}
        .trend-up{color:var(--accent)}.trend-down{color:var(--danger)}
        .chart-wrapper{background:var(--bg-card);border-radius:var(--radius);padding:1.5rem;border:1px solid var(--border)}
        .chart-container{height:300px;position:relative}
        .chart-bars{display:flex;align-items:flex-end;height:200px}
        .bar{flex:1;background:linear-gradient(180deg,var(--accent),#00f5c4);border-radius:4px 4px 0 0;position:relative;min-height:10px;transition:height .5s}
        .bar-value{position:absolute;bottom:-1.5rem;font-size:.75rem;font-weight:600}
        .bar-label{font-size:.65rem;margin-top:.4rem;color:var(--text-muted);text-align:center}
        .client-form{background:var(--bg-card);border-radius:var(--radius);padding:1.5rem;border:1px solid var(--border);margin-bottom:1.5rem}
        .form-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:1rem}
        .form-group{display:flex;flex-direction:column;gap:.5rem}
        .form-group label{font-size:.8rem;color:var(--text-muted)}
        .form-group input,.form-group select,.form-group textarea{background:var(--bg);border:1px solid var(--border);color:var(--text);padding:.8rem;border-radius:6px}
        .form-group input:focus,.form-group select:focus,.form-group textarea:focus{outline:none;border-color:var(--accent)}
        .form-actions{display:flex;gap:1rem;justify-content:flex-end}
        .btn{padding:.8rem 1.5rem;border-radius:6px;font-weight:600;cursor:pointer;border:none;font-size:.9rem}
        .btn-primary{background:var(--accent);color:#fff}.btn-primary:hover{background:var(--accent-hover)}
        .btn-secondary{background:var(--bg);color:var(--text);border:1px solid var(--border)}.btn-secondary:hover{background:var(--border)}
        .client-table{width:100%;border-collapse:collapse;margin-top:1rem}
        .client-table th,.client-table td{padding:.8rem;text-align:left;border-bottom:1px solid var(--border)}
        .client-table th{background:var(--bg);color:var(--text-muted);font-size:.85rem;font-weight:600}
        .client-table tr:hover{background:var(--bg)}
        .status-badge{padding:.3rem .8rem;border-radius:20px;font-size:.75rem;font-weight:600;display:inline-block}
        .status-hot{background:rgba(239,68,68,.1);color:var(--danger)}.status-warm{background:rgba(245,158,11,.1);color:var(--warning)}.status-cold{background:rgba(59,130,246,.1);color:var(--info)}
        .client-actions{display:flex;gap:.5rem}.btn-small{padding:.4rem .8rem;border-radius:4px;font-size:.8rem;border:none}
        .btn-view{background:var(--accent);color:#fff}.btn-edit{background:var(--info);color:#fff}.btn-delete{background:var(--danger);color:#fff}
        .tabs{display:flex;gap:.5rem;margin-bottom:1.5rem;border-bottom:1px solid var(--border)}
        .tab{padding:.8rem 1.5rem;border:none;color:var(--text-muted);cursor:pointer;font-size:.9rem;border-bottom:2px solid transparent}
        .tab.active{color:var(--accent);border-bottom-color:var(--accent)}.tab:hover{color:var(--text)}
        .tab-content{display:none}.tab-content.active{display:block}
        .activity-list{max-height:400px;overflow-y:auto;display:flex;flex-direction:column;gap:.8rem}
        .activity-item{background:var(--bg);border-radius:8px;padding:1rem;border:1px solid var(--border);display:flex;align-items:center;gap:.8rem}
        .activity-dot{width:8px;height:8px;border-radius:50%}
        .activity-content{flex:1}.activity-text{font-size:.85rem;color:var(--text)}.activity-time{font-size:.7rem;color:var(--text-muted)}
        .modal{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,.7);align-items:center;justify-content:center;z-index:1000}
        .modal.active{display:flex}
        .modal-content{background:var(--bg-card);border-radius:var(--radius);padding:2rem;border:1px solid var(--border);max-width:600px;width:100%}
        .modal-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:1.5rem;border-bottom:1px solid var(--border)}
        .modal-title{font-size:1.3rem;font-weight:700;color:var(--text)}
        .close-modal{background:none;border:none;color:var(--text-muted);font-size:1.5rem;cursor:pointer}
        .sales-summary{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem;margin-bottom:1.5rem}
        .summary-card{background:var(--bg-card);border-radius:var(--radius);padding:1.5rem;border:1px solid var(--border);text-align:center}
        .summary-icon{width:40px;height:40px;border-radius:8px;display:inline-flex;align-items:center;justify-content:center;font-size:1.2rem;margin-bottom:.5rem}
        .summary-value{font-size:1.8rem;font-weight:700;color:var(--text)}
        .summary-label{font-size:.85rem;color:var(--text-muted)}
        .summary-value.positive{color:var(--success)}.summary-value.negative{color:var(--danger)}
        .sales-table{width:100%;border-collapse:collapse}
        .sales-table th,.sales-table td{padding:.8rem;text-align:left;border-bottom:1px solid var(--border)}
        .sales-table th{background:var(--bg);color:var(--text-muted)}
        .chat-container{background:var(--bg-card);border-radius:var(--radius);padding:1.5rem;border:1px solid var(--border);margin-top:1rem}
        .chat-messages{height:300px;overflow-y:auto;display:flex;flex-direction:column;gap:.8rem}
        .chat-msg{padding:.8rem 1rem;border-radius:var(--radius);max-width:85%;word-wrap:break-word}
        .chat-msg.user{background:var(--accent);color:#fff;align-self:flex-end;border-bottom-right-radius:4px}
        .chat-msg.ia{background:var(--bg);color:var(--text);align-self:flex-start;border-bottom-left-radius:4px;border:1px solid var(--border)}
        .chat-input{display:flex;gap:.5rem;margin-top:1rem}
        .chat-input input{flex:1;background:var(--bg);border:1px solid var(--border);color:var(--text);padding:.8rem;border-radius:6px}
        .chat-input button{background:var(--accent);color:#fff;border:none;padding:.8rem;border-radius:6px;cursor:pointer}
        @media(max-width:768px){.container{padding:1rem}.filters{padding:.8rem 1rem}.metric-value{font-size:1.5rem}.chart-container{height:180px}}
    </style>
</head>
<body>
<div class="container">
    <header><div class="header-inner"><div class="logo"><div class="logo-icon">PR</div><div class="logo-text">PRISMA IA<span>Dashboard</span></div></div><div class="header-actions"><select id="periodFilter"><option>7 dias</option><option selected>30 dias</option><option>90 dias</option></select></div></div></header>

    <div class="filters">
        <label>Setor</label><select id="sectorFilter"><option value="all">Todos</option><option value="atacado">Atacado</option><option value="varejo">Varejo</option><option value="clinicas">Clínicas</option><option value="automotivo">Automotivo</option><option value="advocacia">Advocacia</option><option value="imobiliaria">Imobiliária</option><option value="contadores">Contadores</option><option value="lojas">Lojas</option><option value="tiktok">TikTok</option></select>
        <label>Canal</label><select id="channelFilter"><option value="all">Todos</option><option value="whatsapp">WhatsApp</option><option value="email">E-mail</option><option value="instagram">Instagram</option><option value="facebook">Facebook</option><option value="tiktok">TikTok</option></select>
        <label>Status</label><select id="statusFilter"><option value="all">Todos</option><option value="hot">Quente</option><option value="warm">Morno</option><option value="cold">Frio</option></select>
    </div>

    <div class="tabs">
        <button class="tab active" data-tab="overview">Visão Geral</button>
        <button class="tab" data-tab="clients">Dados dos Clientes</button>
        <button class="tab" data-tab="conversations">Conversas IA</button>
        <button class="tab" data-tab="sales_results">Resultado de Vendas</button>
        <button class="tab" data-tab="sectors">Por Setor</button>
    </div>

    <div class="tab-content active" id="overview">
        <div class="grid-2">
            <div class="metric-card"><div class="metric-header"><span class="metric-title">Leads Quentes</span><i class="fas fa-fire" style="color:var(--danger)"></i></div><div class="metric-value" id="hotCount">0</div><div class="metric-trend trend-up"><i class="fas fa-arrow-up"></i><span>Alta probabilidade</span></div></div>
            <div class="metric-card"><div class="metric-header"><span class="metric-title">Leads Mornos</span><i class="fas fa-thermometer-half" style="color:var(--warning)"></i></div><div class="metric-value" id="warmCount">0</div><div class="metric-trend"><i class="fas fa-arrow-up"></i><span>Potencial moderado</span></div></div>
            <div class="metric-card"><div class="metric-header"><span class="metric-title">Leads Frios</span><i class="fas fa-snowflake" style="color:var(--info)"></i></div><div class="metric-value" id="coldCount">0</div><div class="metric-trend trend-down"><i class="fas fa-arrow-down"></i><span>Reaquecimento</span></div></div>
            <div class="metric-card"><div class="metric-header"><span class="metric-title">Taxa Conversão</span><i class="fas fa-chart-line" style="color:var(--accent)"></i></div><div class="metric-value" id="conversionRate">24.8%</div><div class="metric-trend"><i class="fas fa-arrow-up"></i><span>Aumento</span></div></div>
        </div>
        <div class="chart-wrapper"><div class="section-title">Distribuição de Status</div><div class="chart-container"><div class="chart-bars" id="statusChart"></div></div></div>
    </div>

    <div class="tab-content" id="clients">
        <div class="client-form"><div class="section-title">CADASTRO de Clientes</div>
            <form id="clientForm">
                <div class="form-grid">
                    <div class="form-group"><label>Nome</label><input type="text" id="clientName" required></div>
                    <div class="form-group"><label>Setor</label><select id="clientSector" required><option value="">Selecione</option><option value="atacado">Atacado</option><option value="varejo">Varejo</option><option value="clinicas">Clínicas</option><option value="automotivo">Automotivo</option><option value="advocacia">Advocacia</option><option value="imobiliaria">Imobiliária</option><option value="contadores">Contadores</option><option value="lojas">Lojas</option><option value="tiktok">TikTok</option></select></div>
                    <div class="form-group"><label>Canal</label><select id="clientChannel" required><option value="">Selecione</option><option value="whatsapp">WhatsApp</option><option value="email">E-mail</option><option value="instagram">Instagram</option><option value="facebook">Facebook</option><option value="tiktok">TikTok</option></select></div>
                    <div class="form-group"><label>Telefone</label><input type="tel" id="clientPhone" placeholder="(00) 00000-0000"></div>
                    <div class="form-group"><label>E-mail</label><input type="email" id="clientEmail" placeholder="email@exemplo.com"></div>
                    <div class="form-group"><label>Valor (R$)</label><input type="number" id="clientValue" step="0.01" required></div>
                    <div class="form-group"><label>Status</label><select id="clientStatus" required><option value="hot">Quente</option><option value="warm" selected>Morno</option><option value="cold">Frio</option></select></div>
                </div>
                <div class="form-group"><label>Observações</label><textarea id="clientNotes" rows="3"></textarea></div>
                <div class="form-actions"><button type="button" class="btn btn-secondary" id="clearForm">Limpar</button><button type="submit" class="btn btn-primary">Cadastrar</button></div>
            </form>
        </div>
        <div class="client-table-container">
            <div class="section-title">Lista de Clientes</div>
            <table class="client-table"><thead><tr><th>Cliente</th><th>Setor</th><th>Canal</th><th>Valor</th><th>Tel</th><th>E-mail</th><th>Status</th><th>Ações</th></tr></thead><tbody id="clientTableBody"></tbody></table>
        </div>
    </div>

    <div class="tab-content" id="conversations">
        <div class="section-title">Conversas IA</div>
        <div class="chat-container"><div class="chat-messages" id="chatClinicas"></div><div class="chat-input"><input type="text" id="inputClinicas" placeholder="Mensagem..."><button id="sendClinicasBtn">Enviar</button></div></div>
        <div class="chat-container" style="margin-top:2rem"><div class="chat-messages" id="chatPacientes"></div><div class="chat-input"><input type="text" id="inputPaciente" placeholder="Mensagem..."><button id="sendPacienteBtn">Enviar</button></div></div>
    </div>

    <div class="tab-content" id="sales_results">
        <div class="section-title">Resultado de Vendas</div>
        <div class="sales-summary">
            <div class="summary-card"><div class="summary-icon" style="background:rgba(16,185,129,.1);color:#10b981"><i class="fas fa-dollar-sign"></i></div><div class="summary-value" id="totalRevenue">R$ 0</div><div class="summary-label">Faturamento</div></div>
            <div class="summary-card"><div class="summary-icon" style="background:rgba(59,130,246,.1);color:#3b82f6"><i class="fas fa-shopping-cart"></i></div><div class="summary-value" id="totalDeals">0</div><div class="summary-label">Vendas</div></div>
            <div class="summary-card"><div class="summary-icon" style="background:rgba(245,158,11,.1);color:#f59e0b"><i class="fas fa-percentage"></i></div><div class="summary-value" id="conversionRate">0%</div><div class="summary-label">Conversão</div></div>
            <div class="summary-card"><div class="summary-icon" style="background:rgba(139,92,246,.1);color:#8b5cf6"><i class="fas fa-user-check"></i></div><div class="summary-value" id="avgTicket">R$ 0</div><div class="summary-label">Ticket Médio</div></div>
        </div>
        <div class="sales-table-container">
            <div class="section-title">Detalhes de Vendas</div>
            <table class="sales-table"><thead><tr><th>Cliente</th><th>Setor</th><th>Data</th><th>Cat.</th><th>Leads</th><th>Prop.</th><th>Vend.</th><th>Valor</th></tr></thead><tbody id="salesTableBody"></tbody></table>
        </div>
    </div>

    <div class="tab-content" id="sectors"><div class="section-title">Desempenho por Setor</div><div class="grid-4" id="sectorsGrid"></div></div>

    <div style="background:var(--bg-card);border-radius:var(--radius);padding:1.5rem;border:1px solid var(--border);margin-top:2rem"><div class="section-title">Atividade Recente</div><div class="activity-list" id="activityList"></div></div>

    <div id="editModal" class="modal"><div class="modal-content">
        <div class="modal-header"><h2 class="modal-title">Editar Cliente</h2><button class="close-modal" id="closeModal">&times;</button></div>
        <form id="editForm">
            <input type="hidden" id="editClientId">
            <div class="form-group"><label>Nome</label><input type="text" id="editClientName" required></div>
            <div class="form-group"><label>Setor</label><select id="editClientSector" required><option value="atacado">Atacado</option><option value="varejo">Varejo</option><option value="clinicas">Clínicas</option><option value="automotivo">Automotivo</option><option value="advocacia">Advocacia</option><option value="imobiliaria">Imobiliária</option><option value="contadores">Contadores</option><option value="lojas">Lojas</option><option value="tiktok">TikTok</option></select></div>
            <div class="form-group"><label>Canal</label><select id="editClientChannel" required><option value="whatsapp">WhatsApp</option><option value="email">E-mail</option><option value="instagram">Instagram</option><option value="facebook">Facebook</option><option value="tiktok">TikTok</option></select></div>
            <div class="form-group"><label>Telefone</label><input type="tel" id="editClientPhone"></div>
            <div class="form-group"><label>E-mail</label><input type="email" id="editClientEmail"></div>
            <div class="form-group"><label>Valor (R$)</label><input type="number" id="editClientValue" step="0.01" required></div>
            <div class="form-group"><label>Status</label><select id="editClientStatus" required><option value="hot">Quente</option><option value="warm">Morno</option><option value="cold">Frio</option></select></div>
            <div class="form-group"><label>Observações</label><textarea id="editClientNotes" rows="3"></textarea></div>
            <div class="form-actions"><button type="submit" class="btn btn-primary">Salvar</button><button type="button" class="btn btn-secondary" id="cancelEdit">Cancelar</button></div>
        </form>
    </div></div>
</div>

<script>
const API = '/api';
const fmt = (v) => 'R$ ' + Number(v).toLocaleString('pt-BR', { minimumFractionDigits: 2 });
let currentFilters = { sector: 'all', channel: 'all', status: 'all' };

async function fetchJSON(url, options = {}) {
  const res = await fetch(url, { headers: { 'Content-Type': 'application/json' }, ...options });
  if (!res.ok) { const err = await res.json().catch(()=>({})); throw new Error(err.error || `HTTP ${res.status}`); }
  return res.json();
}
function showAlert(msg) { alert(msg); }

// --- RENDER ---
function renderClientTable(clients) {
  const tbody = document.getElementById('clientTableBody'); tbody.innerHTML = '';
  if (!clients.length) { tbody.innerHTML = '<tr><td colspan="8" style="text-align:center;padding:2rem;color:var(--text-muted)">Nenhum cliente</td></tr>'; return; }
  clients.forEach(c => {
    const tr = document.createElement('tr');
    tr.innerHTML = `<td><strong>${c.name}</strong></td><td>${c.sector}</td><td>${c.channel}</td><td>${fmt(c.value)}</td><td>${c.phone||'N/A'}</td><td>${c.email||'N/A'}</td><td><span class="status-badge status-${c.status}">${c.status==='hot'?'Quente':c.status==='warm'?'Morno':'Frio'}</span></td><td><div class="client-actions"><button class="btn btn-small btn-view" data-id="${c.id}">Ver</button><button class="btn btn-small btn-edit" data-id="${c.id}">Edit</button><button class="btn btn-small btn-delete" data-id="${c.id}">Delete</button></div></td>`;
    tbody.appendChild(tr);
  });
}

function renderMetrics(data) {
  document.getElementById('hotCount').textContent = data.hot;
  document.getElementById('warmCount').textContent = data.warm;
  document.getElementById('coldCount').textContent = data.cold;
  document.getElementById('totalRevenue').textContent = fmt(data.totalValue);
  document.getElementById('totalDeals').textContent = data.totalDeals;
  document.getElementById('avgTicket').textContent = fmt(data.avgTicket);
  renderStatusChart(data.hot, data.warm, data.cold);
}

function renderStatusChart(hot, warm, cold) {
  const ct = document.getElementById('statusChart'); ct.innerHTML = '';
  const total = hot + warm + cold; if (total === 0) return;
  const data = [{label:'Quente',v:hot,c:'#ef4444'},{label:'Morno',v:warm,c:'#f59e0b'},{label:'Frio',v:cold,c:'#3b82f6'}];
  data.forEach(p => { const b=document.createElement('div'); b.className='bar'; b.style.height=(p.v/total)*100+'%'; b.style.background=p.c; b.innerHTML=`<span class="bar-value">${p.v}</span><span class="bar-label">${p.label}</span>`; ct.appendChild(b); });
}

function renderSalesTable(sales) {
  const tbody = document.getElementById('salesTableBody'); tbody.innerHTML = '';
  if (!sales.length) { tbody.innerHTML = '<tr><td colspan="8" style="text-align:center;padding:2rem;color:var(--text-muted)">Nenhuma venda</td></tr>'; return; }
  sales.forEach(s => { const tr=document.createElement('tr'); tr.innerHTML=`<td>${s.client_name}</td><td>${s.sector}</td><td>${new Date(s.date).toLocaleDateString()}</td><td>${s.category}</td><td>${s.leads}</td><td>${s.proposals}</td><td>${s.sold}</td><td>${fmt(s.value)}</td>`; tbody.appendChild(tr); });
}

function renderSectorsGrid(sectors) {
  const grid = document.getElementById('sectorsGrid'); grid.innerHTML = '';
  const icons = { atacado:'fa-box', varejo:'fa-store', clinicas:'fa-heartbeat', automotivo:'fa-car', advocacia:'fa-gavel', imobiliaria:'fa-home', contadores:'fa-calculator', lojas:'fa-shopping-bag', tiktok:'fa-tiktok' };
  const colors = { atacado:'linear-gradient(135deg,#3b82f6,#1e40af)', varejo:'linear-gradient(135deg,#10b981,#059669)', clinicas:'linear-gradient(135deg,#8b5cf6,#7c3aed)', automotivo:'linear-gradient(135deg,#f59e0b,#d97706)', advocacia:'linear-gradient(135deg,#6366f1,#4f46e5)', imobiliaria:'linear-gradient(135deg,#ec4899,#db2777)', contadores:'linear-gradient(135deg,#06b6d4,#0891b2)', lojas:'linear-gradient(135deg,#f97316,#ea580c)', tiktok:'linear-gradient(135deg,#000000,#333)' };
  sectors.forEach(s => {
    const card = document.createElement('div'); card.className='sector-card';
    card.innerHTML = `<div class="sector-header"><div class="sector-icon" style="background:${colors[s.sector]}"><i class="fas ${icons[s.sector]}"></i></div><div class="sector-title">${s.sector.charAt(0).toUpperCase()+s.sector.slice(1)}</div></div><div class="sector-metrics"><div class="sector-metric"><div class="sector-metric-value">${s.leads}</div><div class="sector-metric-label">Clientes</div></div><div class="sector-metric"><div class="sector-metric-value">${((s.hotCount/s.leads)*100).toFixed(1)}%</div><div class="sector-metric-label">Quentes</div></div><div class="sector-metric"><div class="sector-metric-value">${fmt(s.revenue)}</div><div class="sector-metric-label">Potencial</div></div><div class="sector-metric"><div class="sector-metric-value">-</div><div class="sector-metric-label">Resp. Média</div></div></div>`;
    grid.appendChild(card);
  });
}

function renderActivity(list) {
  const el = document.getElementById('activityList'); el.innerHTML = '';
  list.slice(0,10).forEach(a => { const d=document.createElement('div'); d.className='activity-item'; const dot={'success':'#00d4aa','warning':'#ff8c42','error':'#ff6b6b','info':'#3b82f6'}[a.status]||'#4a90e2'; d.innerHTML=`<div class="activity-dot" style="background:${dot}"></div><div class="activity-content"><div class="activity-text">${a.text}</div><div class="activity-time">${new Date(a.created_at).toLocaleString()}</div></div>`; el.appendChild(d); });
}

// --- CHAT ---
function appendChatMsg(containerId, role, text) {
  const container = document.getElementById(containerId);
  const div = document.createElement('div');
  div.className = `chat-msg ${role}`;
  div.innerHTML = `<strong>${role==='user'?'Você':'PRISMA IA'}:</strong> ${text} ${role==='ia'?'<i class="fas fa-robot" style="margin-left:8px;opacity:.7"></i>':''}`;
  container.appendChild(div);
  container.scrollTop = container.scrollHeight;
}

async function sendChat(inputId, containerId, channel) {
  const input = document.getElementById(inputId);
  const text = input.value.trim(); if (!text) return;
  appendChatMsg(containerId, 'user', text); input.value = '';
  try {
    const { reply } = await fetchJSON(`${API}/chat/${channel}`, { method: 'POST', body: JSON.stringify({ message: text }) });
    appendChatMsg(containerId, 'ia', reply);
  } catch (e) { appendChatMsg(containerId, 'ia', 'Erro ao conectar na IA.'); console.error(e); }
}

async function loadChatHistory(channel, containerId) {
  try {
    const msgs = await fetchJSON(`${API}/chat/${channel}`);
    msgs.forEach(m => appendChatMsg(containerId, m.role, m.content));
  } catch (e) { console.error('Chat history load failed', e); }
}

// --- DATA LOADING ---
async function loadClients() {
  const params = new URLSearchParams(currentFilters).toString();
  try {
    const clients = await fetchJSON(`${API}/clients?${params}`);
    renderClientTable(clients);
  } catch (e) { console.error(e); showAlert('Erro ao carregar clientes'); }
}

async function loadMetrics() {
  const params = new URLSearchParams(currentFilters).toString();
  try {
    const data = await fetchJSON(`${API}/stats?${params}`);
    renderMetrics(data);
    const sales = await fetchJSON(`${API}/sales`);
    renderSalesTable(sales);
    const sectors = await fetchJSON(`${API}/sectors`);
    renderSectorsGrid(sectors);
  } catch (e) { console.error(e); }
}

async function loadActivity() {
  try { const act = await fetchJSON(`${API}/activity`); renderActivity(act); } catch (e) { console.error(e); }
}

// --- INIT ---
document.addEventListener('DOMContentLoaded', () => {
  // Tabs
  document.querySelectorAll('.tab').forEach(btn => btn.addEventListener('click', () => {
    document.querySelectorAll('.tab').forEach(b=>b.classList.remove('active'));
    document.querySelectorAll('.tab-content').forEach(c=>c.classList.remove('active'));
    btn.classList.add('active');
    document.getElementById(btn.dataset.tab).classList.add('active');
    if (btn.dataset.tab === 'conversations') { loadChatHistory('clinicas', 'chatClinicas'); loadChatHistory('pacientes', 'chatPacientes'); }
    if (btn.dataset.tab === 'sectors') { loadMetrics(); }
  }));

  // Filters
  ['sectorFilter','channelFilter','statusFilter'].forEach(id => {
    document.getElementById(id).addEventListener('change', e => {
      currentFilters[id.replace('Filter','')] = e.target.value;
      loadClients(); loadMetrics();
    });
  });

  // Client Form
  document.getElementById('clientForm').addEventListener('submit', async e => {
    e.preventDefault();
    const f = e.target;
    const payload = { name:f.clientName.value, sector:f.clientSector.value, channel:f.clientChannel.value, phone:f.clientPhone.value, email:f.clientEmail.value, value:f.clientValue.value, status:f.clientStatus.value, notes:f.clientNotes.value };
    try { await fetchJSON(`${API}/clients`, { method:'POST', body:JSON.stringify(payload) }); f.reset(); loadClients(); loadMetrics(); loadActivity(); showAlert('Cliente cadastrado!'); } catch(e){ showAlert(e.message); }
  });
  document.getElementById('clearForm').addEventListener('click', () => document.getElementById('clientForm').reset());

  // Table Delegation
  document.getElementById('clientTableBody').addEventListener('click', async e => {
    const btn = e.target.closest('button'); if (!btn) return;
    const id = btn.dataset.id;
    if (btn.classList.contains('btn-view')) { const c = await fetchJSON(`${API}/clients/${id}`); alert(`Nome: ${c.name}\nSetor: ${c.sector}\nCanal: ${c.channel}\nValor: ${fmt(c.value)}\nStatus: ${c.status}\nVendas: ${c.sales.length}`); }
    if (btn.classList.contains('btn-edit')) { const c = await fetchJSON(`${API}/clients/${id}`); document.getElementById('editClientId').value=c.id; document.getElementById('editClientName').value=c.name; document.getElementById('editClientSector').value=c.sector; document.getElementById('editClientChannel').value=c.channel; document.getElementById('editClientPhone').value=c.phone; document.getElementById('editClientEmail').value=c.email; document.getElementById('editClientValue').value=c.value; document.getElementById('editClientStatus').value=c.status; document.getElementById('editClientNotes').value=c.notes; document.getElementById('editModal').classList.add('active'); }
    if (btn.classList.contains('btn-delete')) { if(confirm('Excluir permanentemente?')) { try { await fetchJSON(`${API}/clients/${id}`, { method:'DELETE' }); loadClients(); loadMetrics(); loadActivity(); } catch(e){ showAlert(e.message); } } }
  });

  // Edit Modal
  document.getElementById('editForm').addEventListener('submit', async e => {
    e.preventDefault();
    const id = document.getElementById('editClientId').value;
    const payload = { name:document.getElementById('editClientName').value, sector:document.getElementById('editClientSector').value, channel:document.getElementById('editClientChannel').value, phone:document.getElementById('editClientPhone').value, email:document.getElementById('editClientEmail').value, value:document.getElementById('editClientValue').value, status:document.getElementById('editClientStatus').value, notes:document.getElementById('editClientNotes').value };
    try { await fetchJSON(`${API}/clients/${id}`, { method:'PUT', body:JSON.stringify(payload) }); document.getElementById('editModal').classList.remove('active'); loadClients(); loadMetrics(); loadActivity(); showAlert('Atualizado!'); } catch(e){ showAlert(e.message); }
  });
  document.getElementById('closeModal').addEventListener('click', () => document.getElementById('editModal').classList.remove('active'));
  document.getElementById('cancelEdit').addEventListener('click', () => document.getElementById('editModal').classList.remove('active'));

  // Chat
  document.getElementById('sendClinicasBtn').addEventListener('click', () => sendChat('inputClinicas', 'chatClinicas', 'clinicas'));
  document.getElementById('inputClinicas').addEventListener('keypress', e => { if(e.key==='Enter') sendChat('inputClinicas', 'chatClinicas', 'clinicas'); });
  document.getElementById('sendPacienteBtn').addEventListener('click', () => sendChat('inputPaciente', 'chatPacientes', 'pacientes'));
  document.getElementById('inputPaciente').addEventListener('keypress', e => { if(e.key==='Enter') sendChat('inputPaciente', 'chatPacientes', 'pacientes'); });

  async function sendChat(inputId, containerId, channel) {
    const input = document.getElementById(inputId);
    const text = input.value.trim(); if (!text) return;
    appendChatMsg(containerId, 'user', text); input.value = '';
    try {
      const { reply } = await fetchJSON(`${API}/chat/${channel}`, { method: 'POST', body: JSON.stringify({ message: text }) });
      appendChatMsg(containerId, 'ia', reply);
    } catch (e) { appendChatMsg(containerId, 'ia', 'Erro ao conectar na IA.'); console.error(e); }
  }

  function appendChatMsg(containerId, role, text) {
    const container = document.getElementById(containerId);
    const div = document.createElement('div');
    div.className = `chat-msg ${role}`;
    div.innerHTML = `<strong>${role==='user'?'Você':'PRISMA IA'}:</strong> ${text} ${role==='ia'?'<i class="fas fa-robot" style="margin-left:8px;opacity:.7"></i>':''}`;
    container.appendChild(div);
    container.scrollTop = container.scrollHeight;
  }

  async function loadChatHistory(channel, containerId) {
    try {
      const msgs = await fetchJSON(`${API}/chat/${channel}`);
      msgs.forEach(m => appendChatMsg(containerId, m.role, m.content));
    } catch (e) { console.error('Chat history load failed', e); }
  }

  // INITIAL LOAD
  loadClients();
  loadMetrics();
  loadActivity();
});
</script>
</body>
</html>