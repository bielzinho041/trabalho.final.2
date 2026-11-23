:root{
  --bg:#0f1220;
  --bg-alt:#151a2e;
  --card:#1b2138;
  --text:#e9ecf5;
  --muted:#9aa3bd;
  --accent:#6ea8fe;
  --accent-2:#a78bfa;
  --border:#2a3250;
  --radius:14px;
}

*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}

body{
  font-family:'Segoe UI',system-ui,-apple-system,sans-serif;
  background:var(--bg);
  color:var(--text);
  line-height:1.65;
}

/* HERO */
.hero{
  padding:80px 20px 60px;
  max-width:900px;
  margin:0 auto;
  text-align:center;
}
.eyebrow{
  color:var(--accent);
  font-size:.85rem;
  letter-spacing:2px;
  text-transform:uppercase;
  margin-bottom:18px;
}
.hero h1{
  font-size:clamp(1.9rem,4vw,3rem);
  line-height:1.15;
  margin-bottom:22px;
}
.hero h1 span{
  background:linear-gradient(90deg,var(--accent),var(--accent-2));
  -webkit-background-clip:text;
  background-clip:text;
  color:transparent;
}
.hero-text{color:var(--muted);max-width:720px;margin:0 auto 26px}
blockquote{
  border-left:3px solid var(--accent);
  background:var(--card);
  padding:18px 22px;
  text-align:left;
  font-style:italic;
  color:#cdd4e8;
  border-radius:0 var(--radius) var(--radius) 0;
  max-width:720px;
  margin:0 auto 30px;
}
.hero-nav{
  display:flex;
  gap:12px;
  justify-content:center;
  flex-wrap:wrap;
}
.hero-nav a{
  color:var(--text);
  text-decoration:none;
  border:1px solid var(--border);
  padding:10px 18px;
  border-radius:999px;
  font-size:.9rem;
  transition:.2s;
}
.hero-nav a:hover{background:var(--accent);color:#0b0e1a;border-color:var(--accent)}

/* SECTIONS */
.section{
  max-width:1000px;
  margin:0 auto;
  padding:70px 20px;
}
.section-alt{background:var(--bg-alt);max-width:100%;}
.section-alt > *{max-width:1000px;margin-left:auto;margin-right:auto}
.section-title{font-size:clamp(1.5rem,3vw,2rem);margin-bottom:14px}
.section-sub{color:var(--muted);margin-bottom:22px}

.badge{
  display:inline-block;
  background:var(--card);
  border:1px solid var(--border);
  color:var(--accent);
  font-size:.8rem;
  padding:4px 12px;
  border-radius:999px;
  margin-bottom:26px;
}

/* TIMELINE */
.timeline{
  position:relative;
  padding-left:26px;
  border-left:2px solid var(--border);
}
.fase{
  position:relative;
  margin-bottom:34px;
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  padding:22px;
}
.fase::before{
  content:"";
  position:absolute;
  left:-33px;
  top:26px;
  width:12px;
  height:12px;
  border-radius:50%;
  background:var(--accent);
  box-shadow:0 0 0 4px var(--bg);
}
.fase .periodo{color:var(--accent-2);font-size:.8rem;letter-spacing:1px;text-transform:uppercase}
.fase h3{font-size:1.15rem;margin:6px 0 10px}
.fase p{color:var(--muted);font-size:.95rem}
.fase ul{margin:12px 0 12px 20px;color:var(--muted);font-size:.92rem}
.fase .destaque{
  margin-top:12px;
  padding:10px 14px;
  background:rgba(110,168,254,.1);
  border-left:3px solid var(--accent);
  border-radius:6px;
  font-size:.9rem;
}

/* CONTROLES */
.controls{
  display:flex;
  gap:12px;
  flex-wrap:wrap;
  margin-bottom:22px;
}
.controls input,
.controls select{
  background:var(--card);
  border:1px solid var(--border);
  color:var(--text);
  padding:11px 14px;
  border-radius:10px;
  font-size:.95rem;
  outline:none;
  font-family:inherit;
}
.controls input{flex:1;min-width:220px}
.controls input:focus,
.controls select:focus{border-color:var(--accent)}

/* GRID REDAÇÕES */
.grid-redacoes{
  display:grid;
  grid-template-columns:repeat(auto-fill,minmax(260px,1fr));
  gap:18px;
}
.card-redacao{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  padding:20px;
  cursor:pointer;
  transition:.2s;
}
.card-redacao:hover{
  transform:translateY(-4px);
  border-color:var(--accent);
  box-shadow:0 8px 24px rgba(110,168,254,.12);
}
.card-redacao .tema{
  font-size:.72rem;
  letter-spacing:1px;
  text-transform:uppercase;
  color:var(--accent-2);
}
.card-redacao h3{font-size:1rem;margin:8px 0}
.card-redacao .resumo{font-size:.88rem;color:var(--muted)}

.empty-msg{
  text-align:center;
  color:var(--muted);
  padding:40px 20px;
}

/* MODAL */
.modal{
  display:none;
  position:fixed;
  inset:0;
  background:rgba(5,7,15,.8);
  backdrop-filter:blur(4px);
  z-index:100;
  padding:20px;
  overflow-y:auto;
}
.modal.active{display:flex;align-items:flex-start;justify-content:center;padding-top:60px}
.modal-box{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  max-width:720px;
  width:100%;
  padding:30px;
  position:relative;
}
.modal-close{
  position:absolute;
  top:14px;right:18px;
  background:none;border:none;
  color:var(--muted);
  font-size:1.8rem;
  cursor:pointer;
  line-height:1;
}
.modal-close:hover{color:var(--accent)}
.modal-box h3{font-size:1.3rem;margin-bottom:6px;padding-right:30px}
.modal-tema{color:var(--accent-2);font-size:.8rem;text-transform:uppercase;letter-spacing:1px;margin-bottom:18px}
.modal-texto{color:#cdd4e8;white-space:pre-line;font-size:.95rem}

/* FOOTER */
.footer{
  text-align:center;
  padding:40px 20px;
  border-top:1px solid var(--border);
  color:var(--muted);
  font-size:.88rem;
}

@media(max-width:600px){
  .hero{padding:60px 18px 40px}
  .timeline{padding-left:20px}
  .fase::before{left:-27px}
  .modal.active{padding-top:20px}
}
