<footer>  
    <section class="footer_section">
        <ul class="footer_ul">


          <div class="info_div">
            <p>SkoleMad ApS <strong>•</strong> Klaringen 15, 4147 Jystrup</p>
            <p>+45 70 22 29 10 <strong>•</strong>  <a href="mailto:post@skolemad.dk">post@skolemad.dk</a></p>
          </div>

            <!-- kontakt og cv footer -->
            
        <div class="vilkar"> 
            <li>
              <a href="/#/">Vilkår</a>
            </li>
            <li>
              <a href="/#/">Privatlivspolitik</a>
            </li>
          
        </div>
      </ul>

          

    </section>
</footer>

<style>

footer {
  background-color: white;
  padding: 2rem;
}

.info_div p {
  font-family: var(--heading);
  line-height: 1.7rem;
}

<<<<<<< HEAD

=======
.vilkar li {
  line-height: 1.5rem;
}
>>>>>>> 0eb7f8e65f1b428fbf6f8f5ea0649002656f82bb

.vilkar li a:hover { 
  text-decoration: underline;
}


.info_div p a {
  font-family: var(--heading);
}

.info_div {
  padding-bottom: 2rem;
}
ul li a{
  font-family: var(--heading);
  text-decoration: none;
  font-size: 1rem;
}
ul li {
  list-style-type: none;
  
}


@media screen and (min-width: 640px) {

.vilkar {
  padding-top: 1rem;
}
}


@media screen and (min-width: 768px) {

.footer_ul  {
  display: flex;
  justify-content: space-between;
  
}
.vilkar {
  padding-top: 0;
  display: flex;
  gap: 3rem;
  align-items: center;
}


footer {
  padding-left: 3rem;
        padding-right: 3rem;
        padding-top: 3rem;
        padding-bottom: 3rem;
}

.vilkar {
  padding-top: 0;
}

.info_div {
  padding-bottom: 0;
}
}


@media screen and (min-width: 1024px) {

  footer {
    padding-left: 4rem;
        padding-right: 4rem;
    
}

.info_div p {
  
  line-height: 2rem;
}
}


@media screen and (min-width: 1280px) {
  footer {
    padding-left: 4rem;
        padding-right: 4rem;
  }

  .info_div p {
  
  line-height: 2.2rem;
}

}



/* .footer_section,
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
} */

</style>