Apontamentos
<section id="Selectors">

    1. PAI > FILHO      element > element	(div > p)	    
    Selects all <p> elements where the parent is a <div> element 
    <div>
        <p>

    ou

    <div>
        <h1>
        <p>


    2. IRMAO + IRMAO    element+element	(div + p)
    Selects the first <p> element that is placed immediately after <div> elements
    <div>
    <h1>
    <p>


    3. PAI ~ FILHO INDIRECTO  element1~element2	(p ~ ul)	
    Selects every <ul> element that is preceded by a <p> element


</section>

Font-weight: 
    /*300 Light , 400 Regular, 500/600 Medium, 700 Semibold, 800 bold, 900 Black - 400 é o regular */

Quando se usa o Float:
clear:both; /*depois de um float deve ser inserido*/


lógica estrutura html (classes)

<main id="content">
    <div class="container">
        <section class="section product-section">
            <ul class="breadcrumbs"> 
            <div class="banner">
                <figure class="image">
                    <img>
            <div class="banner__detail">
                <h1 class="title is-3"></h1>
                <h2 class="subtitle is-4"></h2>
            <div class="row">
                <div class="column is-3">
                    <div class="card">
                        <div class="card-content">
                            <label>
                                <span class="icon"></span>
                            </label>
                            <div class="control">
                                <label></label>
                                <input></input>
                            </div>
                        </div>
                    </div>
                <div class="column">
                    <div class="card">
                        <div class="card-content">
                            <div class="product-controls">
                                <span></span>
                                <select class="select is-small">
                                    <option></option>
                                </select>
                            </div>
                        <div class="product-list">
                            <div class="row is-multiline">
                                <div class="column is-4">
                                    <article class="product">
                                        <figure class="product-image">
                                            <img>

Sobre Nomenclatura:

Devemos intercalar a semantica Bulmed


