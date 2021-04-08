<template>
  <div>
    <TheNavButton />
    <article class="imprint">
      <h1>Impressum</h1>
      <p>Angaben gemäß § 5 TMG</p>
      <h2>Kontakt</h2>
      <address>
        <p>Universität der Künste Berlin</p>
        <p>
          <a
            href="https://www.udk-berlin.de/studium/architektur/fachgebiete/gebaeudeplanung-und-entwerfen/"
          >
            Fachgebiet Gebäudeplanung und Entwerfen
          </a>
        </p>
        <p>Prof. Markus Bader</p>
        <p>Vertreten durch Anna Kokalanova</p>
        <p>
          E-Mail:
          <a href="mailto:raumproduktion@raumlabor.net">
            raumproduktion@raumlabor.net
          </a>
        </p>
        <p>Telefon: <a href="tel:03031852297">030 / 31852297</a></p>
        <p>Anschrift: Hardenbergstraße 33, 10623 Berlin</p>
      </address>
      <h2>Hinweis</h2>
      <p>
        Die Universität der Künste (UdK) Berlin übernimmt keine Gewähr für die
        Aktualität, Richtigkeit und Vollständigkeit der auf dieser Website
        bereitgestellten Angaben. Dies gilt im besonderen Maße für die Inhalte
        externer Internetseiten, auf die über Hyperlinks direkt oder indirekt
        verwiesen wird und die von der UdK Berlin nicht beeinflusst werden
        können. Die von den Fakultäten, Instituten und weiteren Einrichtungen
        unterbreiteten Angebote unterliegen der Verantwortung der jeweiligen
        Bereiche.
      </p>
      <h2>Haftungsausschluss</h2>
      <h3>Haftung für Inhalte</h3>
      <p>
        Die Inhalte unserer Seiten wurden mit größter Sorgfalt erstellt. Für die
        Richtigkeit, Vollständigkeit und Aktualität der Inhalte können wir
        jedoch keine Gewähr übernehmen. Als Diensteanbieter sind wir gemäß § 7
        Abs.1 TMG für eigene Inhalte auf diesen Seiten nach den allgemeinen
        Gesetzen verantwortlich. Nach §§ 8 bis 10 TMG sind wir als
        Diensteanbieter jedoch nicht verpflichtet, übermittelte oder
        gespeicherte fremde Informationen zu überwachen oder nach Umständen zu
        forschen, die auf eine rechtswidrige Tätigkeit hinweisen.
        Verpflichtungen zur Entfernung oder Sperrung der Nutzung von
        Informationen nach den allgemeinen Gesetzen bleiben hiervon unberührt.
        Eine diesbezügliche Haftung ist jedoch erst ab dem Zeitpunkt der
        Kenntnis einer konkreten Rechtsverletzung möglich. Bei Bekanntwerden von
        entsprechenden Rechtsverletzungen werden wir diese Inhalte umgehend
        entfernen.
      </p>
      <h3>Haftung für Links</h3>
      <p>
        Unser Angebot enthält Links zu externen Webseiten Dritter, auf deren
        Inhalte wir keinen Einfluss haben. Deshalb können wir für diese fremden
        Inhalte auch keine Gewähr übernehmen. Für die Inhalte der verlinkten
        Seiten ist stets der jeweilige Anbieter oder Betreiber der Seiten
        verantwortlich. Die verlinkten Seiten wurden zum Zeitpunkt der
        Verlinkung auf mögliche Rechtsverstöße überprüft. Rechtswidrige Inhalte
        waren zum Zeitpunkt der Verlinkung nicht erkennbar. Eine permanente
        inhaltliche Kontrolle der verlinkten Seiten ist jedoch ohne konkrete
        Anhaltspunkte einer Rechtsverletzung nicht zumutbar. Bei Bekanntwerden
        von Rechtsverletzungen werden wir derartige Links umgehend entfernen.
      </p>
      <h3>Urheberrecht</h3>
      <p>
        Die durch die Seitenbetreiber erstellten Inhalte und Werke auf diesen
        Seiten unterliegen dem deutschen Urheberrecht. Die Vervielfältigung,
        Bearbeitung, Verbreitung und jede Art der Verwertung außerhalb der
        Grenzen des Urheberrechtes bedürfen der schriftlichen Zustimmung des
        jeweiligen Autors bzw. Erstellers. Downloads und Kopien dieser Seite
        sind nur für den privaten, nicht kommerziellen Gebrauch gestattet.
        Soweit die Inhalte auf dieser Seite nicht vom Betreiber erstellt wurden,
        werden die Urheberrechte Dritter beachtet. Insbesondere werden Inhalte
        Dritter als solche gekennzeichnet. Sollten Sie trotzdem auf eine
        Urheberrechtsverletzung aufmerksam werden, bitten wir um einen
        entsprechenden Hinweis. Bei Bekanntwerden von Rechtsverletzungen werden
        wir derartige Inhalte umgehend entfernen.
      </p>
    </article>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.imprint {
  padding: var(--space-s-m);
  margin-left: var(--space-m-l);

  address {
    font-style: normal;
  }

  a {
    font-size: var(--step--1);
  }

  h1 {
    font-size: var(--step-2);
  }

  h2 {
    font-size: var(--step-1);
    margin-top: var(--space-m);
  }

  h2 + * {
    margin-top: var(--space-s);
  }

  h3 {
    font-size: var(--step-0);
    margin-top: var(--space-s);
  }

  h3 + * {
    margin-top: var(--space-xs);
  }

  p {
    font-size: var(--step-0);
  }
}
</style>
