---
title: Storage
slug: storage
order: 06
---

<style>

#page {
  display: flex;
  flex-direction: column-reverse;
}

.large-6,
.medium-6 {
  width:100% !important;
}
.columns > h3 {
  display:none;
}
.doc-list {
  display:flex;
  flex-wrap:wrap;
  margin:0 -15px;
}
.doc-list li {
  padding:15px;
  border-bottom:none !important;
  width:calc(100% / var(--col-nbrs));
}
.doc-list li a {
  align-content:center;
  background:#fafafa;
  border:1px solid #d8d8d8;
  border-radius:8px;
  box-shadow:0 2px 5px rgba(0,0,0,0.16), 0 2px 10px rgba(0,0,0,.12%);
  display:grid;
  font-size:24px;
  height:100%;
  justify-content:center;
  padding:25px 15px;
  text-align:center;
}
.doc-list li a:hover {
  background:#efefef;
}
.doc-list li a,
.doc-list li a:hover,
.doc-list li a:focus,
.doc-list li a:active {
  text-decoration:none !important;
}
.row.product a {
  color: #000 !important;
}
#page a span {
  display:contents;
}
#customProductIndex {
padding:0 25px 15px;
}
#customProductIndex p {
text-align:justify;
}

:root {
  --col-nbrs:1;
}
@media screen and (min-width: 40em) {
:root {
  --col-nbrs:2;
}
}
@media screen and (min-width: 64em) {
:root {
  --col-nbrs:4;
}
}

.doc-list li a:after {
  display:block;
  margin-top:15px;
  text-align:center;
}
.doc-list li a[href~="block-storage"]:after {
  content:"In rutrum orci augue, a sollicitudin libero dictum sit";
}

</style>

<div id="customProductIndex">

<h2>Come utilizzare le soluzioni di storage e backup OVHcloud</h2>

<p>I dati archiviati e i loro diversi utilizzi hanno vincoli specifici e richiedono una soluzione adattata. OVHcloud propone in questa sezione guide e tutorial per comprendere le soluzioni di storage Cloud e adottare il servizio che risponde alle tue necessità: storage di oggetti, per blocco o file, spazio di archiviazione a lungo termine o soluzione di backup. Scopri le soluzioni intorno alle 4 grandi famiglie di storage.</p>
</div>
