<section class="dato_forrige_næste">
    <div class="uge_nummer">
      <p class="lead_p">Uge 12 | d. 21/3 - 25/3</p>
    </div>

    <div class="uger_frem_tilbage">
      <a href="/#/"><p>Forrige uge</p></a>
      <a href="/#/"><p>Næste uge</p></a>
    </div>
  </section>

  <section>
    <div class="tabel">
      <div>
        <p class="dag">Mandag</p>
        <p>Laks med kartofler og persillesovs.</p>
      </div>
      <hr />
      <div>
        <p class="dag">Tirsdag</p>
        <p>Frikadeller, kartoffel- salat og grøntsager.</p>
      </div>
      <hr />
      <div>
        <p class="dag">Onsdag</p>
        <p>Kyllingelår, pastasalat og grøntsagsstænger.</p>
      </div>
      <hr />
      <div>
        <p class="dag">Torsdag</p>
        <p>Lasagne, råkost og flute med smør.</p>
      </div>
      <hr />
      <div>
        <p class="dag">Fredag</p>
        <p>Kartoffelpizza med pesto og vandmelonsalat.</p>
      </div>
    </div>
  </section>

  <section>
    <div class="afbestil">
      <a href="/#/"><p>For at afbestille, klik her.</p></a>
    </div>
  </section>


<style>

.afbestil {
  margin-left: 0rem;
}
.dato_forrige_næste {
  display: flex;
  justify-content: space-between;
  margin-top: 2rem;
  margin-bottom: 0.5rem;
}

.uger_frem_tilbage a {
  color: black;
}

.afbestil a {
  color: black;
}

.afbestil a:hover {
  color: blue;
}

.uger_frem_tilbage a:hover {
  color: blue;
}

.tabel {
  padding-inline: 1rem;
  border: 1px black solid;
  border-radius: 1rem;
}

hr {
  border: 0.1px grey solid;
  width: 18rem;
  margin-inline: auto;
}

.tabel div {
  text-align: center;
  margin-block: 0.7rem;
}

.dag {
  text-decoration: underline;
}

.afbestil {
    margin-top: 1rem;
}

@media (min-width: 640px) {
}

@media (min-width: 768px) {
  .uger_frem_tilbage {
    display: flex;
    gap: 1.5rem;
  }

  hr {
  border: 0.1px grey solid;
  width: 20rem;
  margin-inline: auto;
  }

  .tabel div {
    margin-inline: 0.6rem;
  }
}

@media (min-width: 1024px) {
.tabel {
  display: flex;
}

hr {
  border: 0.1px grey solid;
  width: 0rem;
  height: 5rem;
  margin-block: auto;
  }

  .dag {
      margin-bottom: 0.5rem;
  }
}

</style>