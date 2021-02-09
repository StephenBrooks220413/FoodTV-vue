<template>
  <div class="container">
    <div
      class="p-5 text-center bg-image"
      style="
      background-image: url('https://images.unsplash.com/photo-1572054466274-25b4ed6d6899?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1050&q=80');
      height: 500px;
    "
    >
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <div class="text-white">
            <h1 class="mb-3">About the Chefs</h1>
          </div>
        </div>
      </div>
    </div>
    <br /><br />
    <div class="container">
      <h5>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus
        dolorem adipisci vero saepe minus sit deleniti fuga laboriosam!
        Reiciendis unde earum tempora quaerat tempore doloribus placeat
        obcaecati ab odio incidunt! Lorem ipsum dolor sit amet, consectetur
        adipisicing elit. Modi natus temporibus quae magnam quod quam molestiae
        consequatur aut rerum veritatis repellat ab facere explicabo, sapiente
        nesciunt dolor laboriosam quo labore! Lorem ipsum dolor sit amet
        consectetur, adipisicing elit. Beatae inventore ab error veritatis
        distinctio. Modi, explicabo fuga veritatis eius quae placeat nihil
        minima facilis tenetur laboriosam. Odio laborum accusantium nesciunt.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit itaque
        natus, veniam delectus perspiciatis error at animi fugiat eligendi quod
        nemo quis molestiae provident a id nam aliquam voluptate quisquam! ipsum
        ipsum dolor sit amet consectetur adipisicing elit. Hic accusantium iste
        distinctio nisi itaque maiores, repellendus mollitia quasi reprehenderit
        nam alias temporibus natus nihil repudiandae dolorum! Provident saepe
        reprehenderit ipsam!
      </h5>
    </div>
    <br /><br /><br />
    <div class="row">
      <div class="col-md-6">
        <img
          src="https://images.unsplash.com/photo-1601001815853-3835274403b3?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
          alt="cooks"
          width="100%"
          class="img-fluid"
        />
      </div>
      <div class="col-md-6">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil culpa eos
        consectetur neque aspernatur, cum quaerat architecto dolor error quo
        amet assumenda excepturi sed doloribus soluta pariatur quae placeat
        deleniti! <br /><br />
        <hr />
        <h3>Made Fresh from Fresh Ingredients</h3>
        <hr />
        <br />
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button"
                type="button"
                data-mdb-toggle="collapse"
                data-mdb-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                Accordion Item #1
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              aria-labelledby="headingOne"
              data-mdb-parent="#accordionExample"
            >
              <div class="accordion-body">
                <strong>This is the first item's accordion body.</strong> It is
                hidden by default, until the collapse plugin adds the
                appropriate classes that we use to style each element. These
                classes control the overall appearance, as well as the showing
                and hiding via CSS transitions. You can modify any of this with
                custom CSS or overriding our default variables. It's also worth
                noting that just about any HTML can go within the
                <strong>.accordion-body</strong>, though the transition does
                limit overflow.
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingTwo">
              <button
                class="accordion-button collapsed"
                type="button"
                data-mdb-toggle="collapse"
                data-mdb-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                Accordion Item #2
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              aria-labelledby="headingTwo"
              data-mdb-parent="#accordionExample"
            >
              <div class="accordion-body">
                <strong>This is the second item's accordion body.</strong> It is
                hidden by default, until the collapse plugin adds the
                appropriate classes that we use to style each element. These
                classes control the overall appearance, as well as the showing
                and hiding via CSS transitions. You can modify any of this with
                custom CSS or overriding our default variables. It's also worth
                noting that just about any HTML can go within the
                <strong>.accordion-body</strong>, though the transition does
                limit overflow.
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingThree">
              <button
                class="accordion-button collapsed"
                type="button"
                data-mdb-toggle="collapse"
                data-mdb-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                Accordion Item #3
              </button>
            </h2>
            <div
              id="collapseThree"
              class="accordion-collapse collapse"
              aria-labelledby="headingThree"
              data-mdb-parent="#accordionExample"
            >
              <div class="accordion-body">
                <strong>This is the third item's accordion body.</strong> It is
                hidden by default, until the collapse plugin adds the
                appropriate classes that we use to style each element. These
                classes control the overall appearance, as well as the showing
                and hiding via CSS transitions. You can modify any of this with
                custom CSS or overriding our default variables. It's also worth
                noting that just about any HTML can go within the
                <strong>.accordion-body</strong>, though the transition does
                limit overflow.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
