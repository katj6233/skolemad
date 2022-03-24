<section class="dato_forrige_næste">
        <div class="uge_nummer">
          <p>Uge 12 | d. 21/3 - 25/3</p>
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
          .dato_forrige_næste {
  display: flex;
  justify-content: space-between;
  /* margin-inline: 2rem; */
}

.uger_frem_tilbage a {
  color: black;
}

.afbestil {
  margin-left: 2rem;
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
  /* margin-inline: 2rem; */
  padding-inline: 1rem;
  border: 1px black solid;
  border-radius: 1rem;
}

hr {
  border: 0.1px grey solid;
  width: 13rem;
}

.tabel div {
  text-align: center;
  
}

.dag {
  text-decoration: underline;
}

@media (min-width: 640px) {
  /* .tabel {
    margin-inline: 4rem;
  }

  .dato_forrige_næste {
    margin-inline: 4rem;
  } */

  .afbestil {
    margin-left: 4rem;
  }
}

@media (min-width: 768px) {
  /* .dato_forrige_næste {
    margin-inline: 6rem;
  } */

  .uger_frem_tilbage {
    display: flex;
    gap: 1.5rem;
  }
  .tabel {
    display: flex;
    justify-content: space-between;
    /* margin-inline: 6rem; */
  }

  /* .afbestil {
    margin-left: 6rem;
  } */

  hr {
    border: 0.1px grey solid;
    text-align: center;
    width: 0rem;
  }

  .tabel div {
    margin-inline: 0.6rem;
  }
}

@media (min-width: 1024px) {
  /* .dato_forrige_næste {
    margin-inline: 8rem;
  }

  .tabel {
    margin-inline: 8rem;
  } */

  .afbestil {
    margin-left: 8rem;
  }

  hr {
    border: 0.1px grey solid;
    text-align: center;
    width: 0rem;
  }
}
      </style>