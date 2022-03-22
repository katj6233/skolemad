<footer>  
    <section class="footer_section">
        <ul class="footer_ul">
            <!-- kontakt og cv footer -->
            <li>
              <a href="/#/">Vilkår</a>
            </li>
            <li>
              <a href="/#/">Privatlivspolitik</a>
            </li>
          </ul>

          <div class="info_div">
            <p>SkoleMad ApS</p>
            <p>Klaringen 15, 4147 Jystrup</p>
            <p>+45 70 22 29 10</p>
            <p class="mail">post@skolemad.dk</p>
          </div>

    </section>
</footer>

<style>
.footer_section,
.footer_ul {
  display: flex;
}
.footer_section {
  justify-content: space-between;
  background-color: red;
}
.footer_ul {
  gap: 2rem;
  place-self: center;
}
.footer_ul li {
  list-style: none;
}
.footer_ul a {
  color: black;
}
.mail {
    cursor: pointer;
    color: blue;
}
.mail:hover {
    text-decoration: underline;
}

.info_div {
    padding-right: 40px;
    line-height: 0.5rem;
}

</style>