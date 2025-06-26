<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Kings - Softair Team</title>
  <style>
    /* Reset base */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Trebuchet MS', sans-serif;
      background-color: #1c1f1d;
      color: #eaeaea;
      line-height: 1.6;
      background-image: url('https://www.transparenttextures.com/patterns/green-camo.png');
      background-repeat: repeat;
    }

    /* HEADER */
    header {
      background-color: #2f4f2f;
      color: #f0f0f0;
      text-align: center;
      padding: 2rem 1rem;
      border-bottom: 3px solid #556b2f;
    }

    header h1 {
      font-size: 3rem;
      text-transform: uppercase;
      letter-spacing: 3px;
    }

    header p {
      font-style: italic;
      font-size: 1.2rem;
    }

    /* NAV */
    nav ul {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      list-style: none;
      background-color: transparent;
      padding: 0.5rem;
    }

    nav ul li {
      margin: 0.5rem;
    }

    nav ul li a {
      text-decoration: none;
      color: #cddc39;
      padding: 0.5rem 1rem;
      background-color: #1b1b1b;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    nav ul li a:hover {
      background-color: #556b2f;
      color: #fff;
    }

    /* SECTIONS */
    section {
      padding: 2rem;
      border-bottom: 2px solid #444;
      background-color: rgba(0, 0, 0, 0.6);
    }

    section h2 {
      font-size: 2rem;
      color: #cddc39;
      border-left: 5px solid #556b2f;
      padding-left: 0.5rem;
      margin-bottom: 1rem;
    }

    /* LISTS */
    ul {
      padding-left: 1.5rem;
    }

    ul li {
      margin-bottom: 0.5rem;
    }

    /* BLOCKQUOTE */
    blockquote {
      background-color: #2f2f2f;
      border-left: 5px solid #cddc39;
      padding: 1rem;
      margin: 1rem 0;
      font-style: italic;
      color: #d4d4aa;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #2f4f2f;
      color: #ccc;
      font-size: 0.9rem;
    }

    /* LINKS */
    a {
      color: #90ee90;
    }

    a:hover {
      color: #cddc39;
      text-decoration: underline;
    }

    /* Responsive */
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        align-items: center;
      }

      header h1 {
        font-size: 2.2rem;
      }

      section {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>The Kings</h1>
    <p>Softair con Passione e Onore</p>
    <nav>
      <ul>
        <li><a href="#chi-siamo">Chi Siamo</a></li>
        <li><a href="#valori">Valori</a></li>
        <li><a href="#attivita">Attività</a></li>
        <li><a href="#equipaggiamento">Equipaggiamento</a></li>
        <li><a href="#galleria">Galleria</a></li>
        <li><a href="#testimonianze">Testimonianze</a></li>
        <li><a href="#faq">FAQ</a></li>
        <li><a href="#contatti">Contatti</a></li>
        <li><a href="#lettera-ammissioni">Lettera Ammissioni</a></li>
      </ul>
    </nav>
  </header>

  <section id="chi-siamo">
    <h2>Chi Siamo</h2>
    <p>
      Fondati nel 2025, The Kings sono una squadra di softair con base a Pizzo, Calabria, Italia. Un gruppo unito da passione, strategia e rispetto per il gioco. Ci distinguiamo per spirito di squadra e disciplina.
    </p>
  </section>

  <section id="valori">
    <h2>Valori e Obiettivi</h2>
    <p>
      Il nostro team si fonda su valori solidi: rispetto, lealtà, disciplina, inclusione e passione. 
      L'obiettivo principale è crescere insieme come squadra, partecipare a competizioni di livello sempre più alto e diffondere una cultura sportiva sana.
    </p>
  </section>

  <section id="attivita">
    <h2>Le Nostre Attività</h2>
    <ul>
      <li>Allenamenti settimanali al parchetto in Via San Sebastiano, Pizzo VV, 89812</li>
      <li>Partecipazione a tornei e eventi nazionali</li>
      <li>Sessioni di formazione tattica</li>
      <li>Organizzazione di eventi aperti al pubblico</li>
    </ul>
  </section>

  <section id="equipaggiamento">
    <h2>Il Nostro Equipaggiamento</h2>
    <p>
      Ogni membro della squadra utilizza attrezzatura testata e selezionata per garantire sicurezza ed efficacia durante le missioni. Tra i nostri strumenti:
    </p>
    <ul>
      <li>Repliche Softair (M4, AK, pistole, sniper, ecc.)</li>
      <li>Gilet tattici e caschi balistici replica</li>
      <li>Radio e sistemi di comunicazione</li>
      <li>Divise mimetiche personalizzate</li>
    </ul>
  </section>

  <section id="galleria">
    <h2>Immagini</h2>
    <p>Immagini delle nostre attività verranno caricate presto.</p>
  </section>

  <section id="testimonianze">
    <h2>Testimonianze dei Membri</h2>
    <blockquote>
      "Entrare nei The Kings ha cambiato il mio modo di vivere lo sport. Una vera famiglia!" - EmanueleB.
    </blockquote>
    <blockquote>
      "Esperienza, adrenalina e rispetto reciproco. Un team incredibile!" - RoccoB.
    </blockquote>
  </section>

  <section id="faq">
    <h2>Domande Frequenti (FAQ)</h2>
    <p><strong>Chi può partecipare?</strong><br />
    Chiunque abbia compiuto 13 anni (con autorizzazione dei genitori se minorenne).</p>

    <p><strong>Devo avere il mio equipaggiamento?</strong><br />
    Ogni membro presente nei The Kings dovrà procurarsi l'equipaggiamento (se possibile anche con i soldi degli sponsor).</p>

    <p><strong>È pericoloso?</strong><br />
    Seguiamo tutte le norme di sicurezza, ed è obbligatorio l’uso di protezioni. (Se non usate, potrebbero comportare alti rischi.)</p>
  </section>

  <section id="contatti">
    <h2>Contattaci</h2>
    <p>📍 Base operativa: Pizzo, Calabria, Italia</p>
    <p>📧 Email: <a href="mailto:kingssoftair6@gmail.com">kingssoftair6@gmail.com</a></p>
    <p>📞 Telefono: +39 379 229 5615 / 371 598 3696</p>
    <p>📷 Instagram: <a href="#">@the_kings_2k25</a></p>
  </section>

  <section id="lettera-ammissioni">
    <h2>Lettera Ammissioni</h2>
    <p>
      Lettera di ammissione alle competizioni ufficiali federali di Softair – Squadra “THE KINGS” – Pizzo Calabro (VV)
    </p>
    <p>
      Pizzo Calabro, lì 23/06/2025
    </p>
    <p>
      Spett.le Federazione,<br /><br />
      Con la presente, l’Associazione Sportiva Dilettantistica “THE KINGS”, con sede in Pizzo Calabro (VV), codice CAP 89812, richiede formalmente l’ammissione alle competizioni ufficiali di Softair riconosciute dalla Vostra federazione per la stagione sportiva 2025/2026.
    </p>
    <p>
      La nostra squadra è regolarmente costituita in forma di A.S.D., in conformità alle normative vigenti e agli standard richiesti dal CONI per le discipline sportive riconosciute.
    </p>
    <p>
      Siamo attivi nel territorio calabrese e da tempo ci impegniamo nella promozione del Softair come disciplina sportiva fondata sui valori del fair play, della strategia tattica, della preparazione fisica e della collaborazione di squadra.
    </p>
    <p>Alleghiamo alla presente:</p>
    <ul>
      <li>Copia dell’atto costitutivo e dello statuto dell’associazione;</li>
      <li>Elenco aggiornato dei membri tesserati;</li>
      <li>Copia dell’affiliazione CONI (se già disponibile);</li>
      <li>Certificati medici in corso di validità per tutti i partecipanti;</li>
      <li>Modulo di iscrizione/adesione alle gare (se previsto).</li>
    </ul>
    <p>
      Certi di un vostro positivo riscontro, restiamo a disposizione per qualsiasi ulteriore documentazione o chiarimento.
    </p>
    <p> Cordiali saluti, <br /> Il Presidente dell’A.S.D. “THE KINGS” </p>
  </section>

  <footer>
    <p>© 2025 The Kings, Softair Team | Tutti i diritti riservati</p>
  </footer>

</body>
</html>
