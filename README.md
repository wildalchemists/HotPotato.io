# HotPotato.io
<!DOCTYPE html>
<html lang="es">
<head>
<script>
// ============================================================
//  HOT POTATO — ARCHIVO DE DATOS DEL PITCH
//  Wild Alchemists · 2025
//
//  INSTRUCCIONES:
//  Edita este archivo para actualizar todo el pitch automáticamente.
//  Guarda y recarga el navegador. No toques index.html.
// ============================================================

const PITCH_DATA = {

  studio: {
    nombre:   "Wild Alchemists",
    email:    "wildalchemists@gmail.com",
    instagram:"@wild.alchemists",
    año:      "2025",
    contacto: "Pilar Martín Peña",
  },

  hero: {
    titulo:   "HOT POTATO",
    subtitulo:"El party brawler online donde nadie tiene el control. Gratis para empezar. 2 minutos de caos puro con tus amigos.",
    emoji:    "🥔",
    premios: [
      { icono:"🥉", texto:"3º Premio del Jurado · Match in Games 2025" },
      { icono:"💡", texto:"Mejor Idea · CYL Game Show 2025" },
      { icono:"🏆", texto:"Premio del Público · Match in Games 2025" },
    ],
  },

  concepto: {
    titulo:"PILLA-PILLA CON UN TWIST",
    tarjetas:[
      { num:"01", titulo:"Gratis para empezar",     texto:"Early access gratuito elimina la fricción. La barrera de entrada es cero — entra, juega, invita amigos. Monetización cuando ya están enganchados." },
      { num:"02", titulo:"Mecánica invertida",       texto:"Llevas la patata caliente. Tu objetivo es deshacerte de ella antes de que acabe el tiempo. El portador pierde — nadie quiere el poder." },
      { num:"03", titulo:"Caos puro en 2 min",       texto:"Obstáculos, power-ups y un escenario impredecible. Cada partida es distinta. Nadie sabe qué va a pasar — ni tú." },
      { num:"04", titulo:"Diseñado para grupos",     texto:"El pack 9.99€ incluye 3 keys. Compras el juego y ya tienes con quién jugar. El producto se vende a sí mismo dentro del grupo." },
    ],
  },

  gameplay: {
    titulo:"UNA PARTIDA SON 2 MINUTOS",
    pasos:[
      { num:"01", titulo:"EARLY ACCESS GRATUITO",   texto:"Descarga sin fricción. El jugador entra sin pagar — experimenta el caos antes de comprometerse." },
      { num:"02", titulo:"PATATA ASIGNADA RANDOM",     texto:"Un jugador aleatorio arranca con la patata. El caos empieza desde el segundo 1." },
      { num:"03", titulo:"PERSECUCIÓN + OBSTÁCULOS", texto:"Golpea, esquiva, usa el escenario. El portador intenta pasarla, el resto huye." },
      { num:"04", titulo:"CONVERSIÓN NATURAL",       texto:"Tras 3–5 partidas el jugador compra el pack social (9.99€ + 3 keys) para invitar a sus amigos." },
    ],
    stats:[
      { label:"Duración de partida", valor:"2 MIN" },
      { label:"Jugadores por sala",         valor:"2–10" },
      { label:"Curva de aprendizaje",       valor:"~30 SEG" },
    ],
    estado:    "Early access — gratis",
    plataforma:"Steam PC",
    roadmap:   "Mobile · Consolas (año 2-3)",
  },

  mercado: {
    cagr:     "5.12%",
    cagr_desc:"CAGR del mercado global de juegos casuales 2024–2030. De 19.4B$ a 26.5B$. Fácil acceso, integración social y comunidades activas son los drivers principales.",
    target_chips:["16–28 años","Jugadores casuales con amigos","Fans del caos y clips virales","Streamers de contenido social","Urbanos · ocio digital","Ex-jugadores de Fall Guys"],
    competidores:[
      { emoji:"🟣", nombre:"Fall Guys",   detalle:"Party battle royale · Mediatonic · Casual",  peak:"447K" },
      { emoji:"👾", nombre:"Gang Beasts", detalle:"Brawler físico · Boneloaf · Party",           peak:"27K"  },
      { emoji:"👻", nombre:"R.E.P.O.",     detalle:"Co-op caótico · Semiwork · 2025 · $9.99",     peak:"271K" },
    ],
  },

  posicionamiento: {
    uvp_quote:  "El party game donde nadie tiene el control — ni siquiera tú",
    uvp_explain:"Caos puro en 2 minutos. Gratis para empezar. Para quien quiere jugar ya, no aprender.",
    diferencias:[
      { icono:"🆓", titulo:"GRATIS PARA ENTRAR — VIRAL POR DISEÑO",     texto:"Early access gratuito elimina fricción. El pack social (9.99€ + 3 keys) convierte la compra en un acto entre amigos." },
      { icono:"⚡", titulo:"MÁS RÁPIDO Y CAÓTICO QUE FALL GUYS",         texto:"Micro-partidas de 2 min vs los 15–20 min de Fall Guys. Más sesiones, más clips, más momentum viral." },
      { icono:"🔀", titulo:"MECÁNICA QUE NO EXISTE EN NINGÚN COMPETIDOR", texto:"Querer perder el poder es la mecánica central. Eso genera momentos imposibles de encontrar en cualquier otro juego." },
    ],
  },

  negocio: {
    precio_basico:      4.99,
    precio_social:      9.99,
    steam_cut:          0.30,
    precio_social_desc: "Juego completo + 3 keys para invitar amigos",
    early_access_desc:  "Gratis durante early access — conversión a pago tras el hook",

    inversion_min:   30000,
    inversion_max:   30000,
    equity_sugerido: 15,       // % equity — valoración pre-money implícita: ~200.000€
    breakeven_meses: "8–10",

    uso_fondos:[
      { label:"Arte & animación final",      pct:17, euros:"5.000€"  },
      { label:"Marketing & lanzamiento",     pct:27, euros:"8.000€"  },
      { label:"Freelancers específicos",     pct:25, euros:"7.500€"  },
      { label:"Ferias + servidores + legal", pct:14, euros:"4.100€"  },
      { label:"Licencias + Steam + ops",     pct:17, euros:"5.400€"  },
    ],

    proyecciones:[
      { año:"Año 1", unidades:6000,  ingresos_min:25000, ingresos_max:35000  },
      { año:"Año 2", unidades:12000, ingresos_min:50000, ingresos_max:70000  },
      { año:"Año 3", unidades:20000, ingresos_min:95000, ingresos_max:120000 },
    ],

    milestones:[
      { titulo:"GDD · Documento de diseño",         detalle:"Concepto, mecánicas y setting definidos",          estado:"done",    tag:"Completado"  },
      { titulo:"Prototipo jugable",                  detalle:"Demo en ferias — 3 premios obtenidos",             estado:"done",    tag:"Completado"  },
      { titulo:"Early access gratuito en Steam",    detalle:"Lanzamiento free para tracción y feedback real",   estado:"active",  tag:"En progreso" },
      { titulo:"Arte final · personajes y entorno",  detalle:"3–4 meses tras funding",                          estado:"pending", tag:"Pendiente"   },
      { titulo:"Versión de pago — lanzamiento",     detalle:"Mes 12 desde inversión",                          estado:"pending", tag:"Año 1"       },
      { titulo:"Post-launch · skins, mapas, modos", detalle:"Updates periódicos post-lanzamiento",             estado:"pending", tag:"Año 2"       },
      { titulo:"Expansión a consolas",              detalle:"Switch, PS5, Xbox",                               estado:"pending", tag:"Año 3"       },
    ],
  },

  // 10 personas — esto ES un argumento inversor
  equipo: {
    descripcion:"10 personas. Fundado en la universidad, operando como estudio independiente desde 2024. Arte, código y audio cubiertos internamente. 3 premios en ferias antes del lanzamiento.",
    contacto:   "Pilar Martín Peña — wildalchemists@gmail.com",
    miembros:[
      { iniciales:"PM", nombre:"Pilar Martín Peña",  rol:"Game Designer & Producer · Studio Lead",   tags:["Diseño de juego","Producción","Studio lead"] },
      { iniciales:"ML", nombre:"Marco López",         rol:"Game Designer",                            tags:["Mecánicas","Level design","GDD"] },
      { iniciales:"IH", nombre:"Iván Heredia",        rol:"Programmer",                               tags:["Unity","C#","Gameplay systems"] },
      { iniciales:"IV", nombre:"Iván Vidrier",        rol:"Programmer · Online Systems",              tags:["Netcode","Multiplayer","Servidores"] },
      { iniciales:"JB", nombre:"JoseLuis Bartha",     rol:"Programmer · Game Mechanics",              tags:["Physics","Gameplay loop","C#"] },
      { iniciales:"AC", nombre:"Andrea Carandang",    rol:"2D Artist & Illustrator",                  tags:["Personajes","Ilustración","UI art"] },
      { iniciales:"MM", nombre:"María Merchante",     rol:"Artist & VFX",                             tags:["VFX","Arte 2D","Animación"] },
      { iniciales:"CL", nombre:"César Lorenzo",       rol:"3D Artist",                                tags:["Modelado 3D","Entornos","Personajes"] },
      { iniciales:"MJ", nombre:"Mikel Julián",        rol:"VFX Technical Artist",                     tags:["Shaders","VFX técnico","Part-time"] },
      { iniciales:"IL", nombre:"Isaac López",         rol:"Audio Designer",                           tags:["Sound design","Música","SFX"] },
    ],
    valores:[
      { icono:"🎨", titulo:"ARTE PROPIO RECONOCIBLE",    texto:"IP visual con personalidad única — los personajes ya tienen fanbase tras las ferias. Difícil de replicar con dinero." },
      { icono:"⚙️", titulo:"EQUIPO COMPLETO DESDE DÍA 1", texto:"Arte, código y audio cubiertos internamente. Sin dependencia de freelances para el núcleo del producto." },
    ],
  },

  leanCanvas: {
    problema:{
      items:[
        "No existe un pilla-pilla multijugador online bien ejecutado",
        "Party games populares tienen sesiones largas y curva de entrada alta",
        "Falta un juego caótico de 5 min que funcione sin coordinación previa",
        "Validado en CYL Game Show 2025 — Premio del Público entre 4.000 asistentes y 40+ estudios indie",
      ],
      warning:"",
    },
    solucion:{
      items:[
        "Early access gratuito — cero fricción de entrada",
        "Mecánica invertida: quieres perder el poder, no acumularlo",
        "Pack social 9.99€ + 3 keys: la compra ya incluye a tus amigos",
      ],
      warning:"",
    },
    uvp:{
      frase:  "El party game donde nadie tiene el control — ni siquiera tú",
      detalle:"Caos puro en 2 minutos. Gratis para empezar. Para quien quiere jugar ya, no aprender.",
      warning:"",
    },
    ventaja:{
      items:[
        "Premio del Público en CYL Game Show — votado favorito por 4.000 asistentes reales",
        "3 premios en 2 ferias nacionales: Match in Games (jurado industria) + CYL Game Show (jurado + público)",
        "10 personas: arte, código y audio cubiertos sin freelances externos",
        "IP visual reconocible — personajes con fanbase generada en demo pública",
      ],
      warning:"",
    },
    segmentos:{
      early:[
        "16–28 años, jugadores casuales con grupo de amigos online",
        "Streamers de clips cortos que buscan contenido caótico",
        "Comunidades de Discord de party games",
      ],
      secundario:[
        "Fans de Fall Guys que buscan algo más rápido",
        "Jugadores mobile dando el salto a PC",
      ],
      warning:"",
    },
    metricas:{
      items:[
        "Descargas early access (target: 5.000 en primer mes)",
        "Conversión free → pago (target: 15–20%)",
        "Retención D7 (target: >40% — benchmark party games)",
        "Reviews positivas Steam (target: >80% para el algoritmo)",
        "Partidas por sesión (target: >3 — indica engagement real)",
      ],
      warning:"",
    },
    canales:{
      items:[
        "Steam early access gratuito (principal)",
        "TikTok / Instagram — clips de momentos caóticos",
        "Ferias: CYL, Match in Games, Madrid Games Week",
        "Comunidades Discord y Reddit r/indiegaming",
        "Pack social 9.99€ — el producto se distribuye entre amigos",
      ],
      nota:"→ Consolas (Switch, PS5, Xbox) en año 2-3",
      warning:"",
    },
    costes:{
      confirmados:[
        "Licencias software (Unity, Adobe, etc.) — 500€/año",
        "Servidores multijugador (Photon/Mirror) — 500€ año 1",
        "Ferias año 1 — 2 ferias × 1.000€ = 2.000€",
        "Freelancers específicos (sonido, arte puntual) — 7.500€",
        "Fee Steam — 100€ · Legal / constitución empresa — 1.500€",
      ],
      por_detallar:[
        "Arte & animación final (equipo interno) — 5.000€",
        "Marketing digital y launch campaign — 8.000€",
        "Colchón operativo / imprevistos — 4.900€",
      ],
      inversion:  "30.000€",
      breakeven:  "mes 8–10",
      desglose_total: "12.100€ costes directos + 17.900€ arte, marketing y operaciones = 30.000€",
      warning:"",
    },
    ingresos:{
      modelo:[
        "Early access gratuito → conversión a 4.99€",
        "Pack social 9.99€ + 3 keys (tier recomendado)",
        "Cosmetics / Skins post-launch",
        "DLC de mapas y modos (año 2)",
      ],
      proyeccion:[
        "Año 1: 25–35K€ (6.000 uds de pago)",
        "Año 2: 50–70K€ (12.000 uds)",
        "Año 3: 95–120K€ (20.000 uds)",
      ],
      warning:"Target: 10.000 wishlists → ~6.000 ventas año 1 (60% conversión anual, dato real 2025). Coste paid: ~1.50€/wishlist = 15.000€ máx. TikTok viral puede reemplazarlo gratis.",
    },
  },

  cta:{
    titulo:        "ÚNETE A LA PARTIDA",
    ask_cantidad:  "30.000€",
    ask_equity:    "15%",
    ask_valoracion:"~200.000€",
    descripcion:   "Buscamos 30.000€ a cambio del 15% de Wild Alchemists Studio.\nValoración pre-money implícita: ~200.000€.\n\n35% Arte & animación · 30% Marketing de lanzamiento\n25% Sueldos y operaciones · 10% Legal y publishing\n\nBreak-even estimado mes 8–10. Beneficio acumulado a 3 años: 90–120K€.",
    btn_primario:  "CONTACTAR A WILD ALCHEMISTS →",
    btn_secundario:"Solicitar demo jugable",
  },

};

</script>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hot Potato — Pitch · Wild Alchemists</title>


<meta name="description" content="Hot Potato — Chaotic online party brawler by Wild Alchemists. Early access free. 10-person team. 3 awards. Seeking 30.000€ investment.">
<meta property="og:title" content="Hot Potato — Pitch Deck · Wild Alchemists">
<meta property="og:description" content="El party brawler online donde nadie tiene el control. Early access gratuito. 10 personas. 3 premios. Buscamos 30.000€.">
<meta property="og:type" content="website">
<meta property="og:image" content="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Potato_pe_fond_alb.jpg/320px-Potato_pe_fond_alb.jpg">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Hot Potato — Pitch Deck · Wild Alchemists">
<meta name="twitter:description" content="El party brawler online donde nadie tiene el control. Early access gratuito. 3 premios en ferias.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bangers&family=Space+Mono:wght@400;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
:root{--cream:#EDE8DF;--dark:#131210;--gold:#C9A428;--gold-l:#F0D060;--text:#1A1814;--muted:#6B6560;--card:#F7F3EC;--border:rgba(0,0,0,0.12);}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;scroll-snap-type:y mandatory;}
body{background:var(--cream);color:var(--text);font-family:'DM Sans',sans-serif;overflow-x:hidden;}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:100;display:flex;justify-content:space-between;align-items:center;padding:14px 40px;background:rgba(237,232,223,0.92);backdrop-filter:blur(12px);border-bottom:1px solid var(--border);}
.nav-logo{font-family:'Bangers',cursive;font-size:22px;letter-spacing:2px;color:var(--dark);}
.nav-logo span{color:var(--gold);}
.nav-dots{display:flex;gap:8px;align-items:center;}
.nav-dot{width:8px;height:8px;border-radius:50%;background:var(--border);cursor:pointer;transition:background .2s,transform .2s;border:none;}
.nav-dot:hover,.nav-dot.active{background:var(--gold);transform:scale(1.3);}
.nav-cta{font-family:'Space Mono',monospace;font-size:11px;padding:7px 16px;background:var(--dark);color:var(--gold);border:none;border-radius:4px;cursor:pointer;letter-spacing:.05em;text-decoration:none;transition:background .2s;}
.nav-cta:hover{background:#2a2820;}

/* SECTIONS */
section{min-height:100vh;scroll-snap-align:start;scroll-snap-stop:always;display:flex;flex-direction:column;justify-content:center;padding:100px 60px 60px;position:relative;overflow:hidden;}

/* TYPOGRAPHY */
.lbl{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:.2em;text-transform:uppercase;color:var(--gold);margin-bottom:12px;}
.lbl-light{font-family:'Space Mono',monospace;font-size:10px;letter-spacing:.2em;text-transform:uppercase;color:var(--gold);margin-bottom:12px;}
.ttl{font-family:'Bangers',cursive;font-size:clamp(44px,6vw,80px);letter-spacing:3px;color:var(--dark);line-height:1;margin-bottom:36px;}
.ttl-w{font-family:'Bangers',cursive;font-size:clamp(44px,6vw,72px);letter-spacing:3px;color:#fff;line-height:1;margin-bottom:24px;}
.ttl-w span{color:var(--gold);}

/* HERO */
#hero{background:var(--dark);color:var(--cream);padding:80px 60px 60px;align-items:flex-start;}
.hero-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center;max-width:1100px;width:100%;}
.hero-ey{font-family:'Space Mono',monospace;font-size:11px;letter-spacing:.15em;color:var(--gold);text-transform:uppercase;margin-bottom:16px;}
.hero-t{font-family:'Bangers',cursive;font-size:clamp(72px,10vw,120px);letter-spacing:4px;line-height:.95;color:#fff;margin-bottom:24px;}
.hero-t span{color:var(--gold);display:block;}
.hero-sub{font-family:'Space Mono',monospace;font-size:13px;line-height:1.7;color:rgba(237,232,223,.65);max-width:400px;margin-bottom:36px;}
.awards{display:flex;flex-direction:column;gap:8px;}
.aw-chip{display:inline-flex;align-items:center;gap:10px;background:rgba(201,164,40,.12);border:1px solid rgba(201,164,40,.35);border-radius:6px;padding:8px 14px;font-family:'Space Mono',monospace;font-size:11px;color:var(--gold-l);width:fit-content;}
.hero-vis{display:flex;align-items:center;justify-content:center;position:relative;height:400px;}
.potato{font-size:180px;animation:float 3s ease-in-out infinite;filter:drop-shadow(0 20px 40px rgba(201,164,40,.3));user-select:none;line-height:1;}
.ring{position:absolute;border-radius:50%;border:2px solid rgba(201,164,40,.2);animation:pring 2s ease-in-out infinite;}
.ring:nth-child(1){width:250px;height:250px;}
.ring:nth-child(2){width:310px;height:310px;animation-delay:.5s;border-color:rgba(201,164,40,.1);}
@keyframes float{0%,100%{transform:translateY(0) rotate(-2deg);}50%{transform:translateY(-16px) rotate(2deg);}}
@keyframes pring{0%,100%{transform:scale(1);opacity:.5;}50%{transform:scale(1.06);opacity:1;}}

/* FREE BADGE */
.free-badge{display:inline-flex;align-items:center;gap:6px;background:rgba(60,160,80,.15);border:1px solid rgba(60,160,80,.3);border-radius:6px;padding:7px 14px;font-family:'Space Mono',monospace;font-size:11px;color:#70D080;margin-bottom:20px;}

/* CONCEPT */
#concept{background:var(--cream);}
.concept-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;max-width:1000px;}
.cc{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:28px 22px;transition:transform .2s,box-shadow .2s;}
.cc:hover{transform:translateY(-4px);box-shadow:0 12px 32px rgba(0,0,0,.1);}
.cc-num{font-family:'Bangers',cursive;font-size:48px;color:var(--gold);line-height:1;margin-bottom:12px;}
.cc h3{font-family:'Space Mono',monospace;font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:.08em;color:var(--dark);margin-bottom:8px;}
.cc p{font-size:13px;color:var(--muted);line-height:1.6;}

/* GAMEPLAY */
#gameplay{background:var(--dark);color:var(--cream);}
.gp-grid{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center;max-width:1100px;}
.steps{display:flex;flex-direction:column;gap:20px;margin-top:8px;}
.step{display:flex;gap:16px;}
.step-n{font-family:'Bangers',cursive;font-size:28px;color:var(--gold);min-width:36px;line-height:1;}
.step strong{font-family:'Space Mono',monospace;font-size:12px;display:block;color:#fff;margin-bottom:3px;}
.step span{font-size:13px;color:rgba(237,232,223,.55);line-height:1.5;}
.stat-r{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.08);border-radius:10px;padding:16px 20px;display:flex;justify-content:space-between;align-items:center;}
.stat-l{font-family:'Space Mono',monospace;font-size:11px;color:rgba(237,232,223,.45);text-transform:uppercase;letter-spacing:.08em;}
.stat-v{font-family:'Bangers',cursive;font-size:28px;color:var(--gold);letter-spacing:1px;}
.gp-vis{display:flex;flex-direction:column;gap:12px;}
.pill{display:inline-block;font-family:'Space Mono',monospace;font-size:10px;padding:4px 10px;border-radius:99px;letter-spacing:.06em;}
.pill-g{background:rgba(201,164,40,.15);color:var(--gold-l);border:1px solid rgba(201,164,40,.3);}
.pill-r{background:rgba(208,64,48,.15);color:#F08878;border:1px solid rgba(208,64,48,.3);}
.pill-gr{background:rgba(60,160,80,.15);color:#70D080;border:1px solid rgba(60,160,80,.3);}

/* MARKET */
#market{background:var(--cream);}
.mkt-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:start;max-width:1100px;}
.comp{display:flex;align-items:center;gap:14px;background:var(--card);border:1px solid var(--border);border-radius:10px;padding:14px 18px;margin-bottom:12px;}
.comp-name{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:var(--dark);margin-bottom:2px;}
.comp-detail{font-size:12px;color:var(--muted);}
.comp-peak{font-family:'Bangers',cursive;font-size:22px;color:var(--gold);}
.comp-pl{font-size:10px;color:var(--muted);font-family:'Space Mono',monospace;}
.mkt-big{font-family:'Bangers',cursive;font-size:80px;color:var(--dark);letter-spacing:2px;line-height:1;}
.mkt-big span{color:var(--gold);}
.mkt-desc{font-family:'Space Mono',monospace;font-size:12px;color:var(--muted);line-height:1.7;margin:12px 0 24px;max-width:380px;}
.chips{display:flex;flex-wrap:wrap;gap:8px;}
.chip{font-family:'Space Mono',monospace;font-size:11px;padding:6px 14px;border-radius:6px;background:var(--card);border:1px solid var(--border);color:var(--dark);}

/* POSITIONING */
#positioning{background:#1A1814;color:var(--cream);}
.pos-grid{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center;max-width:1100px;}
.pos-map{position:relative;width:100%;aspect-ratio:1;max-width:420px;margin-bottom:24px;}
.ax{position:absolute;background:rgba(255,255,255,.12);}
.ax.h{height:1px;left:0;right:0;top:50%;}
.ax.v{width:1px;top:0;bottom:0;left:50%;}
.pdot{position:absolute;transform:translate(-50%,-50%);display:flex;flex-direction:column;align-items:center;gap:4px;}
.pdot-c{width:12px;height:12px;border-radius:50%;background:rgba(255,255,255,.3);border:1px solid rgba(255,255,255,.5);}
.pdot.hp .pdot-c{width:18px;height:18px;background:var(--gold);border-color:var(--gold-l);box-shadow:0 0 16px rgba(201,164,40,.6);}
.pdot-l{font-family:'Space Mono',monospace;font-size:9px;color:rgba(237,232,223,.5);text-align:center;white-space:nowrap;}
.pdot.hp .pdot-l{color:var(--gold-l);font-size:10px;font-weight:700;}
.ax-lbl{position:absolute;font-family:'Space Mono',monospace;font-size:9px;color:rgba(237,232,223,.3);letter-spacing:.1em;text-transform:uppercase;}
.ax-lbl.b{bottom:-24px;left:50%;transform:translateX(-50%);}
.ax-lbl.r{right:-8px;top:50%;transform:translateY(-50%) rotate(90deg);}
.uvp-box{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08);border-left:3px solid var(--gold);border-radius:0 10px 10px 0;padding:24px;}
.uvp-q{font-family:'Bangers',cursive;font-size:26px;letter-spacing:1.5px;color:#fff;line-height:1.3;margin-bottom:12px;}
.uvp-e{font-size:13px;color:rgba(237,232,223,.55);line-height:1.6;}
.diffs{display:flex;flex-direction:column;gap:12px;margin-top:28px;}
.diff{display:flex;gap:12px;}
.diff-ic{width:28px;height:28px;border-radius:6px;background:rgba(201,164,40,.12);border:1px solid rgba(201,164,40,.25);display:flex;align-items:center;justify-content:center;font-size:14px;flex-shrink:0;margin-top:2px;}
.diff strong{font-family:'Space Mono',monospace;font-size:11px;color:#fff;display:block;margin-bottom:2px;}
.diff span{font-size:12px;color:rgba(237,232,223,.5);}

/* BUSINESS */
#business{background:var(--cream);}
.biz-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:start;max-width:1100px;}
.price-cards{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:16px;}
.pc{border:1px solid var(--border);border-radius:12px;padding:22px 18px;background:var(--card);}
.pc.feat{border-color:var(--gold);background:#FDF8EC;}
.pc-tier{font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:8px;}
.pc-val{font-family:'Bangers',cursive;font-size:42px;color:var(--dark);letter-spacing:1px;line-height:1;margin-bottom:10px;}
.pc-unit{font-size:20px;}
.pc.feat .pc-val{color:var(--gold);}
.pc-inc{font-size:12px;color:var(--muted);line-height:1.6;}
.pc-net{font-family:'Space Mono',monospace;font-size:10px;color:var(--muted);margin-top:8px;padding-top:8px;border-top:1px solid var(--border);}
.pc-net strong{color:var(--dark);}
.early-note{font-family:'Space Mono',monospace;font-size:11px;color:#3B6D11;background:#EAF3DE;border:1px solid rgba(60,160,80,.2);border-radius:8px;padding:10px 14px;margin-bottom:16px;}
.funds-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:8px;margin-bottom:20px;}
.fund-bar{background:var(--card);border:1px solid var(--border);border-radius:8px;padding:12px 14px;}
.fund-label{font-family:'Space Mono',monospace;font-size:10px;color:var(--muted);margin-bottom:6px;}
.fund-pct{font-family:'Bangers',cursive;font-size:28px;color:var(--gold);letter-spacing:1px;line-height:1;}
.fund-track{height:4px;background:rgba(0,0,0,.08);border-radius:99px;margin-top:6px;overflow:hidden;}
.fund-fill{height:100%;border-radius:99px;background:var(--gold);}
.rev-bar{margin-bottom:10px;}
.rev-bh{display:flex;justify-content:space-between;margin-bottom:5px;}
.rev-bl{font-family:'Space Mono',monospace;font-size:11px;color:var(--muted);}
.rev-bv{font-family:'Bangers',cursive;font-size:18px;color:var(--dark);letter-spacing:1px;}
.rev-t{height:10px;background:rgba(0,0,0,.06);border-radius:99px;overflow:hidden;}
.rev-f{height:100%;border-radius:99px;background:var(--gold);}
.ml-list{display:flex;flex-direction:column;gap:0;margin-top:8px;position:relative;}
.ml-list::before{content:'';position:absolute;left:10px;top:20px;bottom:20px;width:1px;background:var(--border);}
.ml{display:flex;gap:16px;align-items:flex-start;padding:10px 0;}
.ml-dot{width:20px;height:20px;border-radius:50%;border:2px solid var(--border);background:var(--cream);flex-shrink:0;margin-top:2px;display:flex;align-items:center;justify-content:center;font-size:9px;color:var(--muted);position:relative;z-index:1;}
.ml-dot.done{background:var(--gold);border-color:var(--gold);color:#fff;}
.ml-dot.act{border-color:var(--gold);color:var(--gold);}
.ml-title{font-family:'Space Mono',monospace;font-size:11px;font-weight:700;color:var(--dark);margin-bottom:2px;}
.ml-sub{font-size:11px;color:var(--muted);}
.ml-tag{margin-left:auto;font-family:'Space Mono',monospace;font-size:10px;padding:3px 8px;border-radius:4px;white-space:nowrap;flex-shrink:0;}
.mt-d{background:rgba(60,160,80,.12);color:#28a040;}
.mt-a{background:rgba(201,164,40,.12);color:var(--gold);}
.mt-f{background:rgba(0,0,0,.05);color:var(--muted);}

/* TEAM — 10 people */
#team{background:var(--dark);color:var(--cream);}
.team-grid{display:grid;grid-template-columns:1fr 1.6fr;gap:60px;align-items:start;max-width:1100px;}
.team-count{font-family:'Bangers',cursive;font-size:100px;color:var(--gold);line-height:1;letter-spacing:2px;}
.team-count-label{font-family:'Space Mono',monospace;font-size:11px;color:rgba(237,232,223,.45);letter-spacing:.1em;text-transform:uppercase;margin-top:-8px;margin-bottom:16px;}
.team-desc{font-size:13px;color:rgba(237,232,223,.6);line-height:1.7;max-width:320px;margin-bottom:20px;}
.team-aw{display:flex;flex-direction:column;gap:6px;}
.team-aw-row{font-family:'Space Mono',monospace;font-size:11px;color:var(--gold-l);display:flex;align-items:center;gap:8px;}
.team-aw-row::before{content:'🏆';font-size:13px;}
.members-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:8px;}
.mc{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:10px;padding:12px 10px;transition:background .15s;}
.mc:hover{background:rgba(255,255,255,.07);}
.mc-av{width:34px;height:34px;border-radius:50%;background:rgba(201,164,40,.15);border:1px solid rgba(201,164,40,.3);display:flex;align-items:center;justify-content:center;font-family:'Bangers',cursive;font-size:13px;color:var(--gold);margin-bottom:8px;}
.mc-name{font-family:'Space Mono',monospace;font-size:10px;font-weight:700;color:#fff;margin-bottom:2px;line-height:1.3;}
.mc-role{font-size:10px;color:rgba(237,232,223,.4);margin-bottom:6px;line-height:1.3;}
.mc-tags{display:flex;flex-wrap:wrap;gap:3px;}
.mc-tag{font-family:'Space Mono',monospace;font-size:8px;padding:2px 5px;border-radius:3px;background:rgba(255,255,255,.06);color:rgba(237,232,223,.45);}
.vals{display:flex;flex-direction:column;gap:12px;margin-top:20px;}
.val{display:flex;gap:12px;}
.val-ic{width:32px;height:32px;border-radius:7px;background:rgba(255,255,255,.05);display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0;}
.val strong{font-family:'Space Mono',monospace;font-size:11px;color:#fff;display:block;margin-bottom:2px;}
.val span{font-size:12px;color:rgba(237,232,223,.5);}

/* LEAN CANVAS */
#lean-canvas{background:var(--cream);padding:100px 40px 60px;}
.lc-wrap{max-width:1200px;width:100%;}
.lc-grid{display:grid;grid-template-columns:repeat(5,1fr);grid-template-rows:auto auto auto;gap:6px;margin-top:16px;}
.lc{background:var(--card);border:1px solid var(--border);border-radius:10px;padding:12px 14px;min-height:130px;display:flex;flex-direction:column;gap:5px;}
.lc-lbl{font-size:9px;font-weight:700;font-family:'Space Mono',monospace;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:3px;}
.lc-body{font-size:11px;color:var(--text);line-height:1.55;flex:1;}
.lc-body ul{padding-left:14px;}
.lc-body li{margin-bottom:3px;}
.lc-warn{font-size:10px;color:#854F0B;background:#FAEEDA;border-radius:5px;padding:5px 8px;line-height:1.4;}
.lc-warn::before{content:'⚠ ';}
.lc-nota{font-size:10px;color:var(--muted);font-style:italic;}
.lc-uvpq{font-family:'Space Mono',monospace;font-size:11px;font-weight:700;color:var(--dark);margin-bottom:5px;line-height:1.4;}
.lc-ctitle{font-family:'Space Mono',monospace;font-size:9px;font-weight:700;color:var(--dark);margin-bottom:3px;text-transform:uppercase;}
.lc-tag{display:inline-block;font-family:'Space Mono',monospace;font-size:9px;padding:2px 7px;border-radius:99px;margin:2px 2px 0 0;}
.lc-tg{background:#EAF3DE;color:#3B6D11;}
.lc-ta{background:#FAEEDA;color:#854F0B;}
.lc-p{grid-column:1;grid-row:1/3;}
.lc-s{grid-column:2;grid-row:1;}
.lc-u{grid-column:3;grid-row:1/3;}
.lc-adv{grid-column:4;grid-row:1;}
.lc-seg{grid-column:5;grid-row:1/3;}
.lc-m{grid-column:2;grid-row:2;}
.lc-ch{grid-column:4;grid-row:2;}
.lc-co{grid-column:1/4;grid-row:3;}
.lc-co .lc-body{display:grid;grid-template-columns:1fr 1fr;gap:8px;}
.lc-rv{grid-column:4/6;grid-row:3;}
.lc-rv .lc-body{display:grid;grid-template-columns:1fr 1fr;gap:8px;}
.lc-legend{display:flex;gap:16px;margin-top:10px;flex-wrap:wrap;}
.lc-li{display:flex;align-items:center;gap:5px;font-size:11px;color:var(--muted);font-family:'Space Mono',monospace;}
.lc-ld{width:8px;height:8px;border-radius:50%;}

/* CTA — with explicit ask */
#cta{background:var(--dark);color:var(--cream);align-items:center;text-align:center;}
.cta-inner{max-width:760px;width:100%;}
.cta-ttl{font-family:'Bangers',cursive;font-size:clamp(48px,7vw,90px);letter-spacing:4px;color:#fff;line-height:1;margin-bottom:20px;}
.cta-ttl span{color:var(--gold);}
.ask-box{background:rgba(201,164,40,.08);border:1px solid rgba(201,164,40,.25);border-radius:16px;padding:32px 36px;margin-bottom:32px;text-align:left;}
.ask-row{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-bottom:24px;}
.ask-item{}
.ask-item-label{font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:rgba(237,232,223,.4);margin-bottom:6px;}
.ask-item-val{font-family:'Bangers',cursive;font-size:36px;color:var(--gold);letter-spacing:2px;line-height:1;}
.ask-item-sub{font-size:12px;color:rgba(237,232,223,.5);margin-top:4px;}
.ask-divider{border:none;border-top:1px solid rgba(255,255,255,.08);margin:0 0 20px;}
.funds-row{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;}
.fund-item{text-align:center;}
.fund-item-pct{font-family:'Bangers',cursive;font-size:28px;color:#fff;letter-spacing:1px;line-height:1;}
.fund-item-label{font-family:'Space Mono',monospace;font-size:9px;color:rgba(237,232,223,.4);text-transform:uppercase;letter-spacing:.08em;margin-top:3px;line-height:1.4;}
.fund-track-h{height:3px;background:rgba(255,255,255,.1);border-radius:99px;margin-top:6px;overflow:hidden;}
.fund-fill-h{height:100%;border-radius:99px;background:var(--gold);}
.cta-buttons{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;margin-bottom:32px;}
.btn-p{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;letter-spacing:.08em;padding:14px 32px;background:var(--gold);color:var(--dark);border:none;border-radius:8px;cursor:pointer;text-decoration:none;transition:background .2s,transform .15s;}
.btn-p:hover{background:var(--gold-l);transform:translateY(-2px);}
.btn-s{font-family:'Space Mono',monospace;font-size:12px;letter-spacing:.08em;padding:14px 32px;background:transparent;color:rgba(237,232,223,.7);border:1px solid rgba(255,255,255,.15);border-radius:8px;cursor:pointer;text-decoration:none;transition:border-color .2s,transform .15s;}
.btn-s:hover{border-color:rgba(255,255,255,.5);color:#fff;transform:translateY(-2px);}
.contact-row{display:flex;justify-content:center;gap:32px;flex-wrap:wrap;}
.contact-item{font-family:'Space Mono',monospace;font-size:11px;color:rgba(237,232,223,.4);text-decoration:none;transition:color .2s;}
.contact-item:hover{color:var(--gold-l);}

/* REVEAL */
.reveal{opacity:0;transform:translateY(22px);transition:opacity .6s ease,transform .6s ease;}
.reveal.visible{opacity:1;transform:translateY(0);}
.d1{transition-delay:.1s;}.d2{transition-delay:.2s;}.d3{transition-delay:.3s;}.d4{transition-delay:.4s;}

::-webkit-scrollbar{width:4px;}::-webkit-scrollbar-thumb{background:var(--gold);border-radius:2px;}
@media(max-width:768px){
  section{padding:90px 24px 40px;}nav{padding:12px 20px;}.nav-dots{display:none;}
  .hero-grid,.gp-grid,.mkt-grid,.pos-grid,.biz-grid,.team-grid{grid-template-columns:1fr;gap:32px;}
  .concept-grid,.price-cards{grid-template-columns:1fr 1fr;}
  .hero-vis,.ask-row{grid-template-columns:1fr;}.members-grid{grid-template-columns:repeat(2,1fr);}
  .funds-row{grid-template-columns:repeat(2,1fr);}
  .lc-grid{grid-template-columns:1fr 1fr;}.lc-p,.lc-u,.lc-seg,.lc-co,.lc-rv{grid-column:auto;grid-row:auto;}
}

/* DEMO MODAL */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:999;display:flex;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity .25s;}
.modal-overlay.open{opacity:1;pointer-events:all;}
.modal{background:var(--cream);border-radius:16px;padding:36px 40px;max-width:480px;width:90%;position:relative;transform:translateY(16px);transition:transform .25s;}
.modal-overlay.open .modal{transform:translateY(0);}
.modal-close{position:absolute;top:14px;right:16px;background:none;border:none;font-size:20px;cursor:pointer;color:var(--muted);line-height:1;}
.modal-close:hover{color:var(--dark);}
.modal-title{font-family:'Bangers',cursive;font-size:32px;letter-spacing:2px;color:var(--dark);margin-bottom:6px;}
.modal-sub{font-family:'Space Mono',monospace;font-size:11px;color:var(--muted);margin-bottom:24px;line-height:1.6;}
.modal-field{margin-bottom:16px;}
.modal-field label{font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);display:block;margin-bottom:6px;}
.modal-field input,.modal-field textarea,.modal-field select{width:100%;padding:10px 14px;font-family:'DM Sans',sans-serif;font-size:14px;background:#fff;border:1px solid var(--border);border-radius:8px;color:var(--text);transition:border-color .15s;}
.modal-field input:focus,.modal-field textarea:focus,.modal-field select:focus{outline:none;border-color:var(--gold);}
.modal-field textarea{min-height:80px;resize:vertical;line-height:1.6;}
.modal-send{width:100%;padding:13px;font-family:'Space Mono',monospace;font-size:12px;font-weight:700;letter-spacing:.08em;background:var(--dark);color:var(--gold);border:none;border-radius:8px;cursor:pointer;transition:background .2s;margin-top:4px;}
.modal-send:hover{background:#2a2820;}
.modal-sent{text-align:center;padding:16px 0;}
.modal-sent-icon{font-size:40px;margin-bottom:12px;}
.modal-sent-title{font-family:'Bangers',cursive;font-size:28px;letter-spacing:2px;color:var(--dark);margin-bottom:8px;}
.modal-sent-sub{font-family:'Space Mono',monospace;font-size:12px;color:var(--muted);line-height:1.7;}

/* CAMPAIGN SECTION */
#campaign{background:#1A1814;color:var(--cream);}
.camp-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:start;max-width:1100px;}
.camp-timeline{display:flex;flex-direction:column;gap:0;position:relative;margin-top:8px;}
.camp-timeline::before{content:'';position:absolute;left:14px;top:24px;bottom:24px;width:1px;background:rgba(255,255,255,.08);}
.ct-item{display:flex;gap:16px;padding:12px 0;position:relative;}
.ct-dot{width:28px;height:28px;border-radius:50%;background:rgba(201,164,40,.12);border:1px solid rgba(201,164,40,.3);display:flex;align-items:center;justify-content:center;font-size:12px;flex-shrink:0;position:relative;z-index:1;}
.ct-dot.free{background:rgba(60,160,80,.12);border-color:rgba(60,160,80,.3);}
.ct-dot.paid{background:rgba(201,164,40,.2);border-color:rgba(201,164,40,.5);}
.ct-month{font-family:'Space Mono',monospace;font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:rgba(237,232,223,.3);margin-bottom:3px;}
.ct-title{font-family:'Space Mono',monospace;font-size:11px;font-weight:700;color:#fff;margin-bottom:3px;}
.ct-desc{font-size:12px;color:rgba(237,232,223,.5);line-height:1.5;}
.ct-tag{display:inline-block;font-family:'Space Mono',monospace;font-size:9px;padding:2px 7px;border-radius:4px;margin-top:4px;}
.ct-free{background:rgba(60,160,80,.15);color:#70D080;border:1px solid rgba(60,160,80,.25);}
.ct-low{background:rgba(201,164,40,.12);color:var(--gold-l);border:1px solid rgba(201,164,40,.25);}
.ct-paid{background:rgba(208,64,48,.12);color:#F08878;border:1px solid rgba(208,64,48,.25);}
.math-box{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08);border-radius:12px;padding:20px 22px;margin-bottom:16px;}
.math-title{font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:rgba(237,232,223,.4);margin-bottom:14px;}
.math-row{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid rgba(255,255,255,.05);}
.math-row:last-child{border-bottom:none;}
.math-label{font-size:12px;color:rgba(237,232,223,.6);}
.math-val{font-family:'Bangers',cursive;font-size:22px;color:var(--gold);letter-spacing:1px;}
.math-val.ok{color:#70D080;}
.math-val.neutral{color:#fff;}
.insight-chip{background:rgba(201,164,40,.1);border:1px solid rgba(201,164,40,.2);border-radius:8px;padding:12px 14px;font-size:12px;color:rgba(237,232,223,.7);line-height:1.6;margin-top:8px;}
.insight-chip strong{color:var(--gold-l);}
.cost-table{width:100%;margin-top:8px;}
.cost-table tr{border-bottom:1px solid rgba(255,255,255,.05);}
.cost-table tr:last-child{border-bottom:none;}
.cost-table td{padding:8px 0;font-size:12px;}
.cost-table .cost-label{color:rgba(237,232,223,.6);}
.cost-table .cost-val{text-align:right;font-family:'Space Mono',monospace;font-size:11px;color:var(--gold-l);}
.cost-table .cost-val.free{color:#70D080;}
.cost-total td{font-family:'Space Mono',monospace;font-size:12px;font-weight:700;color:#fff;padding-top:12px;}
.cost-total .cost-val{color:var(--gold);}

</style>
</head>
<body>

<nav id="nav">
  <div class="nav-logo">HOT <span>POTATO</span></div>
  <div class="nav-dots" id="nav-dots"></div>
  <a id="nav-cta" class="nav-cta">CONTACTAR →</a>
</nav>

<section id="hero"></section>
<section id="concept"></section>
<section id="gameplay"></section>
<section id="market"></section>
<section id="positioning"></section>
<section id="business"></section>
<section id="team"></section>
<section id="lean-canvas"></section>
<section id="campaign"></section>
<section id="cta"></section>

<script>
const D = PITCH_DATA;
const $ = id => document.getElementById(id);
const ul = items => '<ul>' + items.map(i=>`<li>${i}</li>`).join('') + '</ul>';
const warn = t => t ? `<div class="lc-warn">${t}</div>` : '';
const fmtE = n => n.toLocaleString('es-ES') + '€';

// NAV
const LABELS = ['Intro','Concepto','Gameplay','Mercado','Posición','Negocio','Equipo','Lean Canvas','Campaña','El Ask'];
$('nav-cta').href = `mailto:${D.studio.email}`;
$('nav-cta').textContent = `CONTACTAR →`;
const dotsEl = $('nav-dots');
LABELS.forEach((_,i)=>{ const b=document.createElement('button');b.className='nav-dot'+(i===0?' active':'');b.title=LABELS[i];b.onclick=()=>sections[i].scrollIntoView({behavior:'smooth'});dotsEl.appendChild(b); });

// HERO
const [h1,h2] = D.hero.titulo.split(' ');
$('hero').innerHTML = `
<div class="hero-grid">
  <div>
    <p class="hero-ey reveal">${D.studio.nombre} · ${D.studio.año}</p>
    <h1 class="hero-t reveal d1">${h1}<span>${h2}</span></h1>
    <div class="free-badge reveal d1">🆓 Early access gratuito — sin fricción de entrada</div>
    <p class="hero-sub reveal d2">${D.hero.subtitulo}</p>
    <div class="awards reveal d3">${D.hero.premios.map(p=>`<div class="aw-chip"><span>${p.icono}</span>${p.texto}</div>`).join('')}</div>
  </div>
  <div class="hero-vis reveal d2">
    <div class="ring"></div><div class="ring"></div>
    <div class="potato">${D.hero.emoji}</div>
  </div>
</div>`;

// CONCEPT
$('concept').innerHTML = `
<p class="lbl reveal">El juego</p>
<h2 class="ttl reveal d1">${D.concepto.titulo.replace(' CON ',' <br>CON ')}</h2>
<div class="concept-grid">
  ${D.concepto.tarjetas.map((c,i)=>`<div class="cc reveal d${i+1}"><div class="cc-num">${c.num}</div><h3>${c.titulo}</h3><p>${c.texto}</p></div>`).join('')}
</div>`;

// GAMEPLAY
const [gp1,...gp2] = D.gameplay.titulo.split(' SON ');
$('gameplay').innerHTML = `
<div class="gp-grid">
  <div>
    <p class="lbl-light reveal">Gameplay loop</p>
    <h2 class="ttl-w reveal d1">${gp1}<br>SON <span>${gp2.join(' ')}</span></h2>
    <div class="steps">${D.gameplay.pasos.map((p,i)=>`<div class="step reveal d${i+1}"><div class="step-n">${p.num}</div><div><strong>${p.titulo}</strong><span>${p.texto}</span></div></div>`).join('')}</div>
  </div>
  <div class="gp-vis reveal d2">
    ${D.gameplay.stats.map(s=>`<div class="stat-r"><span class="stat-l">${s.label}</span><span class="stat-v">${s.valor}</span></div>`).join('')}
    <div class="stat-r"><span class="stat-l">Plataforma principal</span><div style="display:flex;flex-direction:column;align-items:flex-end;gap:4px"><span class="pill pill-g">${D.gameplay.plataforma}</span><span class="pill pill-r" style="font-size:9px">${D.gameplay.roadmap}</span></div></div>
    <div class="stat-r"><span class="stat-l">Modelo de entrada</span><span class="pill pill-gr">${D.gameplay.estado}</span></div>
  </div>
</div>`;

// MARKET
const cagrN = D.mercado.cagr.replace('%','');
$('market').innerHTML = `
<p class="lbl reveal">Oportunidad de mercado</p>
<div class="mkt-grid">
  <div>
    <h2 class="ttl reveal d1" style="margin-bottom:16px">MERCADO<br>Y COMPETENCIA</h2>
    ${D.mercado.competidores.map((c,i)=>`<div class="comp reveal d${i+1}"><span style="font-size:22px">${c.emoji}</span><div><div class="comp-name">${c.nombre}</div><div class="comp-detail">${c.detalle}</div></div><div style="margin-left:auto;text-align:right"><div class="comp-peak">${c.peak}</div><div class="comp-pl">peak steam</div></div></div>`).join('')}
  </div>
  <div class="reveal d2">
    <div class="mkt-big">${cagrN}<span>%</span></div>
    <p class="mkt-desc">${D.mercado.cagr_desc}</p>
    <p style="font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:10px">Público objetivo:</p>
    <div class="chips">${D.mercado.target_chips.map(t=>`<span class="chip">${t}</span>`).join('')}</div>
  </div>
</div>`;

// POSITIONING
const pos = D.posicionamiento;
$('positioning').innerHTML = `
<div class="pos-grid">
  <div>
    <p class="lbl-light reveal">Diferenciación</p>
    <h2 class="ttl-w reveal d1" style="font-size:clamp(38px,5vw,60px)">DONDE<br>VIVIMOS<br>EN EL MAPA</h2>
    <div class="diffs">
      ${pos.diferencias.map((d,i)=>`<div class="diff reveal d${i+2}"><div class="diff-ic">${d.icono}</div><div><strong>${d.titulo}</strong><span>${d.texto}</span></div></div>`).join('')}
    </div>
  </div>
  <div class="reveal d2">
    <div class="pos-map">
      <div class="ax h"></div><div class="ax v"></div>
      <div class="pdot" style="left:22%;top:72%"><div class="pdot-c"></div><div class="pdot-l">Among Us</div></div>
      <div class="pdot" style="left:32%;top:52%"><div class="pdot-c"></div><div class="pdot-l">Fall Guys</div></div>
      <div class="pdot" style="left:72%;top:28%"><div class="pdot-c"></div><div class="pdot-l">Fortnite</div></div>
      <div class="pdot" style="left:80%;top:42%"><div class="pdot-c"></div><div class="pdot-l">Rocket League</div></div>
      <div class="pdot hp" style="left:40%;top:26%"><div class="pdot-c"></div><div class="pdot-l">🔥 HOT POTATO</div></div>
      <div class="ax-lbl b">ACCESIBILIDAD (casual → hardcore)</div>
      <div class="ax-lbl r">RITMO (lento → rápido)</div>
    </div>
    <div class="uvp-box reveal d3"><div class="uvp-q">"${pos.uvp_quote}"</div><div class="uvp-e">${pos.uvp_explain}</div></div>
  </div>
</div>`;

// BUSINESS
const neg = D.negocio;
const net1 = (neg.precio_basico*(1-neg.steam_cut)).toFixed(2);
const net2 = (neg.precio_social*(1-neg.steam_cut)).toFixed(2);
const maxR = neg.proyecciones[neg.proyecciones.length-1].ingresos_max;
const bars = neg.proyecciones.map((p,i)=>{
  const pct=Math.round(p.ingresos_max/maxR*100);
  const op=[1,.75,.5][i];
  return `<div class="rev-bar"><div class="rev-bh"><span class="rev-bl">${p.año} · ~${p.unidades.toLocaleString('es-ES')} unidades</span><span class="rev-bv">${fmtE(p.ingresos_min).replace('€','')}–${fmtE(p.ingresos_max)}</span></div><div class="rev-t"><div class="rev-f" style="width:${pct}%;opacity:${op}"></div></div></div>`;
}).join('');
const mls = neg.milestones.map(m=>{
  const dc=m.estado==='done'?'done':m.estado==='active'?'act':'';
  const sym=m.estado==='done'?'✓':m.estado==='active'?'●':'';
  const tc=m.estado==='done'?'mt-d':m.estado==='active'?'mt-a':'mt-f';
  return `<div class="ml"><div class="ml-dot ${dc}">${sym}</div><div><div class="ml-title">${m.titulo}</div><div class="ml-sub">${m.detalle}</div></div><span class="ml-tag ${tc}">${m.tag}</span></div>`;
}).join('');
$('business').innerHTML = `
<p class="lbl reveal">Modelo de negocio</p>
<h2 class="ttl reveal d1">NÚMEROS</h2>
<div class="biz-grid">
  <div>
    <div class="early-note reveal d1">🆓 Early access gratuito → conversión orgánica a pago</div>
    <div class="price-cards reveal d2">
      <div class="pc"><div class="pc-tier">Tier básico</div><div class="pc-val"><span class="pc-unit">€</span>${neg.precio_basico.toFixed(2)}</div><div class="pc-inc">Juego completo en Steam</div><div class="pc-net">Neto tras Steam 30%: <strong>${net1}€</strong></div></div>
      <div class="pc feat"><div class="pc-tier">★ Tier social</div><div class="pc-val"><span class="pc-unit">€</span>${neg.precio_social.toFixed(2)}</div><div class="pc-inc">${neg.precio_social_desc}</div><div class="pc-net">Neto tras Steam 30%: <strong>${net2}€</strong></div></div>
    </div>
    <p style="font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:10px" class="reveal d2">Uso de los 30.000€</p>
    <div class="funds-grid reveal d2">
      ${neg.uso_fondos.map(f=>`<div class="fund-bar"><div class="fund-label">${f.label}</div><div class="fund-pct">${f.pct}%</div><div class="fund-track"><div class="fund-fill" style="width:${f.pct}%"></div></div></div>`).join('')}
    </div>
    <div class="reveal d3">
      <p style="font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:12px">Proyección ingresos netos</p>
      ${bars}
    </div>
  </div>
  <div>
    <p style="font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:12px" class="reveal">Milestones de producción</p>
    <div class="ml-list reveal d2">${mls}</div>
  </div>
</div>`;

// TEAM
const eq = D.equipo;
$('team').innerHTML = `
<div class="team-grid">
  <div>
    <p class="lbl-light reveal">El equipo</p>
    <div class="team-count reveal d1">10</div>
    <div class="team-count-label reveal d1">personas · estudio completo</div>
    <p class="team-desc reveal d2">${eq.descripcion}</p>
    <div class="team-aw reveal d3">${D.hero.premios.map(p=>`<div class="team-aw-row">${p.texto}</div>`).join('')}</div>
    <div class="vals reveal d4">
      ${eq.valores.map(v=>`<div class="val"><div class="val-ic">${v.icono}</div><div><strong>${v.titulo}</strong><span>${v.texto}</span></div></div>`).join('')}
    </div>
  </div>
  <div>
    <div class="members-grid reveal d2">
      ${eq.miembros.map(m=>`<div class="mc"><div class="mc-av">${m.iniciales}</div><div class="mc-name">${m.nombre}</div><div class="mc-role">${m.rol}</div><div class="mc-tags">${m.tags.map(t=>`<span class="mc-tag">${t}</span>`).join('')}</div></div>`).join('')}
    </div>
  </div>
</div>`;

// LEAN CANVAS
const lc = D.leanCanvas;
$('lean-canvas').innerHTML = `
<div class="lc-wrap">
  <p class="lbl reveal">Lean Canvas</p>
  <h2 class="ttl reveal d1" style="margin-bottom:0">MODELO DE NEGOCIO</h2>
  <div class="lc-grid reveal d2">
    <div class="lc lc-p"><div class="lc-lbl">1 · Problema</div><div class="lc-body">${ul(lc.problema.items)}</div>${warn(lc.problema.warning)}</div>
    <div class="lc lc-s"><div class="lc-lbl">2 · Solución</div><div class="lc-body">${ul(lc.solucion.items)}</div>${warn(lc.solucion.warning)}</div>
    <div class="lc lc-u"><div class="lc-lbl">3 · Propuesta de valor única</div><div class="lc-body"><p class="lc-uvpq">"${lc.uvp.frase}"</p><p>${lc.uvp.detalle}</p></div>${warn(lc.uvp.warning)}</div>
    <div class="lc lc-adv"><div class="lc-lbl">4 · Ventaja injusta</div><div class="lc-body">${ul(lc.ventaja.items)}</div>${warn(lc.ventaja.warning)}</div>
    <div class="lc lc-seg"><div class="lc-lbl">5 · Segmentos</div><div class="lc-body"><p class="lc-ctitle">Early adopters:</p>${ul(lc.segmentos.early)}<p class="lc-ctitle" style="margin-top:6px">Secundario:</p>${ul(lc.segmentos.secundario)}</div>${warn(lc.segmentos.warning)}</div>
    <div class="lc lc-m"><div class="lc-lbl">6 · Métricas clave</div><div class="lc-body">${ul(lc.metricas.items)}</div>${warn(lc.metricas.warning)}</div>
    <div class="lc lc-ch"><div class="lc-lbl">7 · Canales</div><div class="lc-body">${ul(lc.canales.items)}</div>${lc.canales.nota?`<div class="lc-nota">${lc.canales.nota}</div>`:''}</div>
    <div class="lc lc-co"><div class="lc-lbl">8 · Estructura de costes</div><div class="lc-body"><div><div class="lc-ctitle">Confirmados:</div>${ul(lc.costes.confirmados)}</div><div><div class="lc-ctitle">A detallar:</div>${ul(lc.costes.por_detallar)}</div></div><div style="display:flex;flex-wrap:wrap;gap:4px;margin-top:5px"><span class="lc-tag lc-ta">Inversión: ${lc.costes.inversion}</span><span class="lc-tag lc-tg">Break-even: ${lc.costes.breakeven}</span></div>${warn(lc.costes.warning)}</div>
    <div class="lc lc-rv"><div class="lc-lbl">9 · Fuentes de ingresos</div><div class="lc-body"><div><div class="lc-ctitle">Modelo:</div>${ul(lc.ingresos.modelo)}</div><div><div class="lc-ctitle">Proyección:</div>${ul(lc.ingresos.proyeccion)}</div></div>${warn(lc.ingresos.warning)}</div>
  </div>
  <div class="lc-legend">
    <div class="lc-li"><div class="lc-ld" style="background:#A32D2D"></div>Incompleto</div>
    <div class="lc-li"><div class="lc-ld" style="background:#3B6D11"></div>Confirmado</div>
    <div class="lc-li"><div class="lc-ld" style="background:#854F0B"></div>Necesita trabajo</div>
  </div>
</div>`;


// CAMPAIGN
$('campaign').innerHTML = `
<div class="camp-grid">
  <div>
    <p class="lbl-light reveal">Estrategia de wishlists</p>
    <h2 class="ttl-w reveal d1">CAMPAÑA<br>PRE-LAUNCH</h2>
    <p style="font-size:13px;color:rgba(237,232,223,.55);line-height:1.7;max-width:380px;margin-bottom:24px" class="reveal d1">
      Target: <strong style="color:var(--gold-l)">10.000 wishlists</strong> antes del launch. Con conversión anual del 60% (dato real Steam 2025) → <strong style="color:var(--gold-l)">6.000 ventas año 1</strong>.
    </p>
    <div class="camp-timeline reveal d2">
      <div class="ct-item">
        <div class="ct-dot free">🎮</div>
        <div>
          <div class="ct-month">Ahora — Mes 1</div>
          <div class="ct-title">STEAM PAGE + CLIPS TIKTOK</div>
          <div class="ct-desc">Publicar clips de 15-30s de los momentos más caóticos de la demo. Ese gameplay caótico es exactamente lo que viraliza en TikTok. Objetivo: 500-1.000 wishlists orgánicos.</div>
          <span class="ct-tag ct-free">0€ — solo tiempo</span>
        </div>
      </div>
      <div class="ct-item">
        <div class="ct-dot free">🎪</div>
        <div>
          <div class="ct-month">Mes 2-3</div>
          <div class="ct-title">STEAM NEXT FEST</div>
          <div class="ct-desc">Solicitar participación con la demo gratuita. El evento más grande de Steam para wishlists — visibilidad orgánica masiva sin coste. Games comparables ganan 2.000-5.000 wishlists en una semana.</div>
          <span class="ct-tag ct-free">0€ — solo demo lista</span>
        </div>
      </div>
      <div class="ct-item">
        <div class="ct-dot ct-dot free">📧</div>
        <div>
          <div class="ct-month">Mes 2-4</div>
          <div class="ct-title">OUTREACH A MICRO-INFLUENCERS</div>
          <div class="ct-desc">Contactar 100-150 creadores de party games en TikTok/YouTube (10K-100K subs). Enviar keys gratis. Tasa de respuesta ~10-15% → 10-15 creadores = alcance potencial de 500K-1M personas.</div>
          <span class="ct-tag ct-low">Keys gratis · ~200€ gestión</span>
        </div>
      </div>
      <div class="ct-item">
        <div class="ct-dot paid">📢</div>
        <div>
          <div class="ct-month">Mes 3-6</div>
          <div class="ct-title">PAID ADS TIKTOK / REDDIT</div>
          <div class="ct-desc">Paid ads de clips de gameplay caótico. Coste real 2025: ~1-1.50€ por wishlist bien optimizado. Presupuesto de 3.000€ → ~2.000-3.000 wishlists adicionales.</div>
          <span class="ct-tag ct-paid">~3.000€ presupuesto</span>
        </div>
      </div>
      <div class="ct-item">
        <div class="ct-dot free">🏆</div>
        <div>
          <div class="ct-month">Mes 4-8</div>
          <div class="ct-title">FERIAS + COMUNIDADES</div>
          <div class="ct-desc">Madrid Games Week, próximas ferias indie. QR en stand → Steam wishlist directo. Discord de party games, r/indiegaming, r/playmygame. Comunidad construida antes del launch.</div>
          <span class="ct-tag ct-low">~2.000€ ferias · comunidades gratis</span>
        </div>
      </div>
    </div>
  </div>
  <div>
    <div class="math-box reveal d2">
      <div class="math-title">Math de wishlists → ventas</div>
      <div class="math-row"><span class="math-label">Target wishlists pre-launch</span><span class="math-val">10.000</span></div>
      <div class="math-row"><span class="math-label">Conversión año 1 (dato real Steam 2025)</span><span class="math-val">60%</span></div>
      <div class="math-row"><span class="math-label">Ventas proyectadas año 1</span><span class="math-val ok">6.000</span></div>
      <div class="math-row"><span class="math-label">ARPU neto medio (~40/60 mix tiers)</span><span class="math-val neutral">5.10€</span></div>
      <div class="math-row"><span class="math-label">Ingresos netos año 1</span><span class="math-val ok">~30.600€</span></div>
    </div>
    <div class="math-box reveal d3">
      <div class="math-title">Coste total de la campaña</div>
      <table class="cost-table">
        <tr><td class="cost-label">TikTok / Instagram clips</td><td class="cost-val free">0€ — orgánico</td></tr>
        <tr><td class="cost-label">Steam Next Fest</td><td class="cost-val free">0€ — gratuito</td></tr>
        <tr><td class="cost-label">Outreach influencers (gestión)</td><td class="cost-val">~200€</td></tr>
        <tr><td class="cost-label">Paid ads (TikTok / Reddit)</td><td class="cost-val">~3.000€</td></tr>
        <tr><td class="cost-label">Ferias (2 × 1.000€)</td><td class="cost-val">~2.000€</td></tr>
        <tr><td class="cost-label">Assets creativos (diseño ads)</td><td class="cost-val">~800€</td></tr>
        <tr class="cost-total"><td class="cost-label">TOTAL CAMPAÑA</td><td class="cost-val">~6.000€</td></tr>
      </table>
    </div>
    <div class="insight-chip reveal d3">
      <strong>Referente real:</strong> un juego indie caótico con solo 1.500 wishlists vendió 200.000 copias en el primer mes — clips de TikTok viralizaron el gameplay. Hot Potato tiene exactamente ese perfil: caos visual, partidas cortas, momentos impredecibles.
    </div>
  </div>
</div>`;

// CTA — explicit ask
const cta = D.cta;
const [ctaA,...ctaB] = cta.titulo.split(' A ');
$('cta').innerHTML = `
<div class="cta-inner">
  <p class="lbl-light reveal" style="color:var(--gold)">La propuesta</p>
  <h2 class="cta-ttl reveal d1">${ctaA} A<br><span>${ctaB.join(' ')}</span></h2>
  <div class="ask-box reveal d2">
    <div class="ask-row">
      <div class="ask-item">
        <div class="ask-item-label">Buscamos</div>
        <div class="ask-item-val">${cta.ask_cantidad}</div>
        <div class="ask-item-sub">inversión inicial</div>
      </div>
      <div class="ask-item">
        <div class="ask-item-label">Equity ofrecido</div>
        <div class="ask-item-val">${cta.ask_equity}</div>
        <div class="ask-item-sub">de Wild Alchemists Studio</div>
      </div>
      <div class="ask-item">
        <div class="ask-item-label">Valoración pre-money</div>
        <div class="ask-item-val">${cta.ask_valoracion}</div>
        <div class="ask-item-sub">break-even mes ${neg.breakeven_meses}</div>
      </div>
    </div>
    <hr class="ask-divider">
    <p style="font-family:'Space Mono',monospace;font-size:10px;text-transform:uppercase;letter-spacing:.1em;color:rgba(237,232,223,.4);margin-bottom:14px">Uso de fondos</p>
    <div class="funds-row">
      ${neg.uso_fondos.map(f=>`<div class="fund-item"><div class="fund-item-pct">${f.pct}%</div><div style="font-family:'Space Mono',monospace;font-size:11px;color:var(--gold-l);margin:2px 0">${f.euros||''}</div><div class="fund-item-label">${f.label}</div><div class="fund-track-h"><div class="fund-fill-h" style="width:${f.pct}%"></div></div></div>`).join('')}
    </div>
  </div>
  <div class="cta-buttons reveal d3">
    <a href="mailto:${D.studio.email}?subject=Hot Potato - Inversión" class="btn-p">${cta.btn_primario}</a>
    <button class="btn-s" onclick="toggleModal(true)">${cta.btn_secundario}</button>
  </div>
  <div class="contact-row reveal d4">
    <a href="mailto:${D.studio.email}" class="contact-item">✉ ${D.studio.email}</a>
    <a href="https://www.instagram.com/${D.studio.instagram.replace('@','')}" class="contact-item" target="_blank">◎ ${D.studio.instagram}</a>
  </div>
</div>`;

// SCROLL
const sections = document.querySelectorAll('section');
const dots = document.querySelectorAll('.nav-dot');
const ro = new IntersectionObserver(e=>e.forEach(x=>{ if(x.isIntersecting) x.target.classList.add('visible'); }),{threshold:.1});
document.querySelectorAll('.reveal').forEach(el=>ro.observe(el));
const so = new IntersectionObserver(e=>e.forEach(x=>{ if(x.isIntersecting){ const i=Array.from(sections).indexOf(x.target);dots.forEach((d,j)=>d.classList.toggle('active',j===i)); } }),{threshold:.5});
sections.forEach(s=>so.observe(s));

// MODAL
function toggleModal(open) {
  document.getElementById('demo-modal').classList.toggle('open', open);
  document.body.style.overflow = open ? 'hidden' : '';
}
function closeModal(e) {
  if (e.target === document.getElementById('demo-modal')) toggleModal(false);
}
function sendDemo() {
  const name   = document.getElementById('dm-name').value.trim();
  const reason = document.getElementById('dm-reason').value.trim();
  const keys   = document.getElementById('dm-keys').value;
  const email  = document.getElementById('dm-email').value.trim();
  if (!name || !reason || !email) {
    alert('Por favor rellena nombre, motivo y email.');
    return;
  }
  const subject = encodeURIComponent('Hot Potato — Solicitud de demo');
  const body = encodeURIComponent(
    'Nombre / Estudio: ' + name + '\n' +
    'Email de contacto: ' + email + '\n' +
    'Keys solicitadas: ' + keys + '\n\n' +
    'Motivo:\n' + reason
  );
  window.location.href = 'mailto:wildalchemists@gmail.com?subject=' + subject + '&body=' + body;
  document.getElementById('modal-body').innerHTML = `
    <div class="modal-sent">
      <div class="modal-sent-icon">🥔</div>
      <div class="modal-sent-title">¡SOLICITUD ENVIADA!</div>
      <p class="modal-sent-sub">Abrimos tu cliente de email con el mensaje listo.<br>Os respondemos en 24–48h con las keys.</p>
    </div>`;
  setTimeout(() => toggleModal(false), 3000);
}
</script>

<!-- DEMO MODAL -->
<div class="modal-overlay" id="demo-modal" onclick="closeModal(event)">
  <div class="modal">
    <button class="modal-close" onclick="toggleModal(false)">✕</button>
    <div id="modal-body">
      <div class="modal-title">SOLICITAR DEMO 🥔</div>
      <p class="modal-sub">Cuéntanos un poco y te enviamos las keys en 24–48h.</p>
      <div class="modal-field">
        <label>Tu nombre y estudio / empresa</label>
        <input type="text" id="dm-name" placeholder="Ej. Ana García — GameIndie Studio">
      </div>
      <div class="modal-field">
        <label>¿Para qué necesitas la demo?</label>
        <textarea id="dm-reason" placeholder="Ej. para evaluarla como inversor, para prensa / review, para un evento, para testeo..."></textarea>
      </div>
      <div class="modal-field">
        <label>¿Cuántas keys necesitas?</label>
        <select id="dm-keys">
          <option value="1">1 key — uso personal</option>
          <option value="2">2 keys</option>
          <option value="4" selected>4 keys — equipo pequeño</option>
          <option value="10">10 keys — evento / prensa</option>
          <option value="otro">Otra cantidad (indicar en el mensaje)</option>
        </select>
      </div>
      <div class="modal-field">
        <label>Tu email de contacto</label>
        <input type="email" id="dm-email" placeholder="tu@email.com">
      </div>
      <button class="modal-send" onclick="sendDemo()">ENVIAR SOLICITUD →</button>
    </div>
  </div>
</div>
</body>
</html>