<template>
  <div class="about">
    <br />
    <h1>Registriraj se</h1>
    <div class="container">
      <div class="row">
        <div class="col-sm"></div>
        <div class="col-sm">
          <form>
            <div class="form-group">
              <label for="exampleInputEmail1">Email adresa</label>
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Upiši email"
              />
            </div>
            <div class="form-group">
              <label for="exampleInputPassword1">Lozinka</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Upiši lozinku"
              />
            </div>
            <div class="form-group">
              <label for="exampleInputPassword1">Ponovi lozinku</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Ponovno upiši lozinku"
              />
            </div>
            <br />
            <button
              type="submit"
              class="btn btn-primary"
              style="background-color: #9e6f49; border: none"
            >
              Nastavi
            </button>
          </form>
        </div>
        <div class="col-sm"></div>
      </div>
    </div>
  </div>
</template>
