<template> 
  <body><br>  
      <div class="d-flex flex-column min-vh-100 justify-content-lg-center align-items-lg-center justify-content-md-end justify-content-sm-end justify-content-end"> 
          <div class="shadow p-4 bg-white rounded-5">
          <div class="container"><br>
            <div class="main-title">
              <h1>Revisão de cadastro</h1>
            </div>
            <br>
            <div class="row">
              <div class="col-lg-6 col-md-12 col-sm-12 col-12">
                <div class="container">
                <div class="row mb-3">
                  <div class="col-lg-12 col-md-12 col-sm-12 col-12">
                    <label class="form-label"><strong>Nome completo</strong></label>
                    <br/>
                    <label class="form-label">Juan Freitas</label>
                  </div>
                </div>
                <div class="row mb-3">
                  <label class="form-label"><strong>CPF</strong></label>
                    <br/>
                    <label class="form-label">XXX.XXX.XXX-XX</label>
                </div>
                <div class="row mb-3">
                  <label class="form-label"><strong>Número de celular ou telefone</strong></label>
                    <br/>
                    <label class="form-label">(00) 0000-0000</label>
                </div>
                <div class="row mb-3">
                  <label class="form-label"><strong>Estado/Cidade</strong></label>
                    <br/>
                    <label class="form-label">São Paulo - São José dos Campos</label>
                </div>   
                <div class="row mb-3">
                  <label class="form-label"><strong>Especialidade principal</strong></label>
                    <br/>
                    <label class="form-label">Cardiologia</label>
                </div>
                <div class="row mb-3">
                  <label class="form-label"><strong>Preço da consulta</strong></label>
                    <br/>
                    <label class="form-label">R$200,00</label>
                </div>
                <div class="row mb-3">
                  <label class="form-label"><strong>Formas de pagamento da consulta</strong></label>
                  <br/>
                  <label class="form-label">Cartão de crédito - Parcelamento em 2x sem juros</label>
                </div>
                <div class="row mb-3">
                  <div class="d-grid gap-2 col-12">
                    <button type="button" class="btn btn-primary" id="register-button">CADASTRAR PROFISSIONAL</button>
                  </div>                
                </div>
                <div class="row justify-content-center">
                  <div class="offset-7">
                    <label class="form-label" id="edit-button">Editar cadastro</label>    
                  </div>
                </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="d-none d-lg-block">
                  <img src="@/assets/desktop-pagina-3.png" class="img-fluid"/>
                </div>
              </div>
              <br>         
          </div>
          </div>
        </div>
      </div>
  </body>
</template>

<style>
#register-button {
  background-color: #FBDE40;
  color: black;
  border-color: transparent;
}

#edit-button {
  font-family: 'Comfortaa', cursive;
  color: #483698;
}
</style>