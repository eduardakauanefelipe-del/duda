<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CARDOSO DETAIL - Estética Automotiva</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

:root{
    --amarelo:#FFD000;
    --azul:#0066FF;
    --azul-escuro:#001B4D;
}

body{
    background:linear-gradient(135deg,#001B4D,#0066FF,#FFD000);
    color:#fff;
    min-height:100vh;
}

/* BARRA SUPERIOR */

.bar{
    background:var(--amarelo);
    color:#000;
    text-align:center;
    padding:10px;
    font-weight:900;
    font-size:13px;
}

/* TOPO */

.topo{
    background:linear-gradient(90deg,#001B4D,#0066FF,#001B4D);
    padding:25px 15px;
    text-align:center;
    border-bottom:4px solid var(--amarelo);
}

.topo h1{
    color:var(--amarelo);
    font-size:32px;
    font-weight:900;
    letter-spacing:2px;
}

.topo h1 span{
    color:#fff;
}

.topo p{
    color:#fff;
    font-size:12px;
    margin-top:6px;
    font-weight:bold;
}

/* CONTAINER */

.container{
    max-width:1100px;
    margin:auto;
    padding:15px;
}

/* TÍTULOS */

h2{
    color:#fff;
    margin:25px 0 15px;
    border-left:6px solid var(--amarelo);
    padding-left:10px;
    text-transform:uppercase;
}

/* PRODUTOS */

.grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:14px;
}

@media(min-width:700px){
    .grid{
        grid-template-columns:repeat(3,1fr);
    }
}

/* CARD */

.card{
    background:#07152b;
    border-radius:16px;
    padding:12px;
    border:2px solid rgba(255,255,255,0.15);
    transition:0.2s;
}

.card:hover{
    border-color:var(--amarelo);
    transform:translateY(-3px);
}

.card img{
    width:100%;
    height:145px;
    object-fit:cover;
    border-radius:12px;
    background:#000;
}

.card h3{
    font-size:14px;
    margin:8px 0 3px;
    color:#fff;
}

.card p{
    font-size:11px;
    color:#bfc9d9;
    height:28px;
}

/* PREÇOS */

.preco-antigo{
    font-size:11px;
    color:#8d96a5;
    text-decoration:line-through;
}

.preco{
    font-size:21px;
    color:var(--amarelo);
    font-weight:900;
}

.parcela{
    font-size:11px;
    color:#bfc9d9;
    margin-bottom:8px;
}

/* BOTÕES */

.btn{
    background:var(--azul);
    color:#fff;
    padding:11px;
    border-radius:30px;
    display:block;
    text-align:center;
    text-decoration:none;
    font-weight:900;
    font-size:13px;
}

.btn:hover{
    background:#0050cc;
}

.btn-amarelo{
    background:var(--amarelo);
    color:#000;
}

/* ETIQUETAS */

.tag{
    background:var(--amarelo);
    color:#000;
    font-size:9px;
    font-weight:900;
    padding:4px 8px;
    border-radius:10px;
    display:inline-block;
    margin-bottom:5px;
}

.tag-azul{
    background:var(--azul);
    color:#fff;
}

/* CONTATO */

.contato{
    margin-top:30px;
    background:linear-gradient(135deg,#001B4D,#0066FF);
    padding:22px;
    border-radius:16px;
    border:2px solid var(--amarelo);
    text-align:center;
}

.contato h3{
    color:var(--amarelo);
}

.contato a{
    background:var(--amarelo);
    color:#000;
    padding:14px 25px;
    border-radius:30px;
    text-decoration:none;
    font-weight:900;
    display:inline-block;
    margin-top:10px;
}

/* RODAPÉ */

.rodape{
    text-align:center;
    padding:25px;
    color:#fff;
    font-size:11px;
    background:#001B4D;
    margin-top:20px;
}

</style>
</head>

<body>

<!-- BARRA -->

<div class="bar">
⚡ CARDOSO DETAIL - ENTREGA EM SARANDI E MARINGÁ | CHAMA NO ZAP 44 99860-3865
</div>

<!-- NOME DA EMPRESA -->

<div class="topo">

<h1>
CARDOSO <span>DETAIL</span>
</h1>

<p>
PRODUTOS PREMIUM DE ESTÉTICA AUTOMOTIVA
</p>

</div>

<div class="container">

<h2>🔥 Produtos em Promoção</h2>

<div class="grid">

<!-- PRODUTO 1 -->

<div class="card">

<span class="tag">MAIS VENDIDO</span>

<img src="https://images.unsplash.com/photo-1600880292089-90a7e086ee0c?w=400">

<h3>Shampoo pH Neutro 500ml</h3>

<p>Alta espuma, não agride a cera</p>

<div class="preco-antigo">De R$49,90</div>

<div class="preco">R$29,90</div>

<div class="parcela">
2x de R$14,95 no cartão
</div>

<a class="btn"
href="https://wa.me/5544998603865?text=Olá Cardoso! Quero o Shampoo por R$29,90">

COMPRAR NO ZAP

</a>

</div>


<!-- PRODUTO 2 -->

<div class="card">

<span class="tag tag-azul">BRILHO EXTREMO</span>

<img src="https://images.unsplash.com/photo-1552930294-6d8008c0f5ac?w=400">

<h3>Cera Carnaúba Pastosa 200g</h3>

<p>Brilho por até 3 meses</p>

<div class="preco-antigo">De R$89,90</div>

<div class="preco">R$59,90</div>

<div class="parcela">
3x de R$19,96 sem juros
</div>

<a class="btn btn-amarelo"
href="https://wa.me/5544998603865?text=Olá Cardoso! Quero a Cera Carnaúba por R$59,90">

COMPRAR NO ZAP

</a>

</div>


<!-- PRODUTO 3 -->

<div class="card">

<img src="https://images.unsplash.com/photo-1603386329225-868f9b1ee6c9?w=400">

<h3>Kit 3 Toalhas Microfibra</h3>

<p>Macia, não risca a pintura</p>

<div class="preco-antigo">De R$69,90</div>

<div class="preco">R$39,90</div>

<div class="parcela">
Pix com desconto
</div>

<a class="btn"
href="https://wa.me/5544998603865?text=Olá Cardoso! Quero o Kit Toalhas R$39,90">

COMPRAR NO ZAP

</a>

</div>


<!-- PRODUTO 4 -->

<div class="card">

<img src="https://images.unsplash.com/photo-1520340356584-f9917d1eea6f?w=400">

<h3>Pretinho Gel Pneu 500ml</h3>

<p>Brilho molhado longa duração</p>

<div class="preco-antigo">De R$39,90</div>

<div class="preco">R$24,90</div>

<div class="parcela">
Entrega hoje
</div>

<a class="btn"
href="https://wa.me/5544998603865?text=Olá Cardoso! Quero Pretinho Gel R$24,90">

COMPRAR NO ZAP

</a>

</div>


<!-- PRODUTO 5 -->

<div class="card">

<span class="tag tag-azul">PROFISSIONAL</span>

<img src="https://images.unsplash.com/photo-1613214149922-f1809c99b414?w=400">

<h3>Descontaminante / Limpa Rodas 500ml</h3>

<p>Remove ferro e piche das rodas</p>

<div class="preco-antigo">De R$59,90</div>

<div class="preco">R$34,90</div>

<div class="parcela">
2x de R$17,45
</div>

<a class="btn"
href="https://wa.me/5544998603865?text=Olá Cardoso! Quero Descontaminante R$34,90">

COMPRAR NO ZAP

</a>

</div>


<!-- PRODUTO 6 -->

<div class="card">

<span class="tag">KIT R$130</span>

<img src="https://images.unsplash.com/photo-1580273916550-e323be2ae537?w=400">

<h3>Kit Iniciante Cardoso Detail</h3>

<p>5 itens pra começar a lucrar</p>

<div class="preco-antigo">De R$199,90</div>

<div class="preco">R$129,90</div>

<div class="parcela">
4x de R$32,47
</div>

<a class="btn btn-amarelo"
href="https://wa.me/5544998603865?text=Olá Cardoso! Quero o KIT INICIANTE por R$129,90">

COMPRAR NO ZAP

</a>

</div>

</div>


<!-- CONTATO -->

<div class="contato">

<h3>
CARDOSO DETAIL - SARANDI PR
</h3>

<p style="margin:10px 0;color:#fff">

Atendimento direto pelo WhatsApp<br>
Entrega rápida | Pagamento Pix / Cartão / Dinheiro

</p>

<a href="https://wa.me/5544998603865?text=Olá! Vim pelo site Cardoso Detail">

CHAMAR NO WHATSAPP<br>
44 99860-3865

</a>

<p style="margin-top:12px;font-size:11px;color:#dbe5f5">

Rua: __________________ • Sarandi - PR

</p>

</div>

</div>


<!-- RODAPÉ -->

<div class="rodape">

<strong>CARDOSO DETAIL © 2026</strong><br>
Produtos Premium de Estética Automotiva<br>
Site nas cores Azul e Amarelo 💙💛

</div>

</body>
</html>
