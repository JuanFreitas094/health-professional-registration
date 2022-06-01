<template> 
  <body><br>  
      <div class="d-flex flex-column min-vh-100 justify-content-lg-center align-items-lg-center justify-content-md-end justify-content-sm-end justify-content-end"> 
        <div class="shadow p-4 bg-white rounded-5">
          <div class="container"><br>
            <div class="main-title">
              <h1>Sobre o profissional</h1>
            </div><br>
            <h3>Dados do profissional</h3>
            <br>
            <div class="row">
              <div class="col-lg-6 col-md-12 col-sm-12 col-12 min-vw-95">
                <div class="row">
                  <div class="col-lg-12 col-md-12 col-sm-12 col-12">
                    <label for="full-name" class="form-label">Nome Completo*</label>
                    <input class="form-control" type="text" id="full-name" placeholder="Nome completo" />
                  </div>
                </div><br>
              
              <div class="row">
                <div class="col-lg-10 col-md-10 col-sm-8 col-8">
                  <label for="cpf" class="form-label">CPF*</label>
                  <input type="text" class="form-control" id="cpf" placeholder="Digite um CPF">
                </div>
              </div><br>
              
              <div class="row">
                <div class="col-lg-10 col-md-10 col-sm-8 col-8">
                  <label for="cellphone" class="form-label">Número do celular*</label>
                  <input type="text" class="form-control" id="cellphone" placeholder="(00) 0 0000-0000">
                </div>
              </div><br>
              
              <div class="row">
                <div class="col-lg-6 col-md-6 cl-sm-6 col-6">
                  <label for="state" class="form-label">Estado*</label>
                  <select class="form-select" aria-label="Default select example" id="state">
                    <option selected>Selecione</option>
                    <option value="1">One</option>
                    <option value="2">Two</option>
                    <option value="3">Three</option>
                  </select>
                </div>

                <div class="col-lg-6 col-md-6 cl-sm-6 col-6">
                  <label for="city" class="form-label">Cidade*</label>
                  <select class="form-select" aria-label="Default select example" id="city">
                    <option selected>Selecione</option>
                    <option value="1">One</option>
                    <option value="2">Two</option>
                    <option value="3">Three</option>
                  </select>
                </div>
              </div><br>

              <div class="row">
                <div class="col-lg-9 col-md-8 col-sm-8 col-8">
                  <div class="progress">
                    <div class="progress-bar" role="progressbar" style="width: 50%" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100"></div>                  
                  </div>
                </div>

                <div class="col-lg-3 col-md-4 col-sm-4 col-4">
                  <label class="form-label" id="progress-label">1 de 2</label>
                </div>
              </div>

              <br/>

              <div class="row">
                <div class="d-grid gap-2 col-12">
                  <button type="button" class="btn btn-primary">PRÓXIMO</button>
                </div>
              </div>

              </div>
              <div class="col-lg-6">
                <div class="d-none d-lg-block">
                  <img src="@/assets/desktop-pagina-1.png" class="img-fluid"/>
                </div>
              </div>
              <br>
            </div>
            <br/>          
          </div>
        </div>
      </div>
  </body>
</template>

<style>
</style>