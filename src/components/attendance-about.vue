<template> 
  <body><br>  
    <div class="d-flex flex-column min-vh-100 justify-content-lg-center align-items-lg-center justify-content-md-end justify-content-sm-end justify-content-end"> 
      <div class="d-flex flex-column align-items-lg-start">
        <router-link to="/">
          <button type="button" class="back-button mb-5">
            <i class="bi bi-chevron-left" style="font-size: 30px; color: #483698;"></i>
          </button>
        </router-link>
        <div class="container p-lg-5 shadow bg-white rounded-5"><br>
          <div class="main-title">
            <h1>Sobre o atendimento</h1>
          </div><br>
          <h3>Detalhes do atendimento</h3>
          <br>
          <div class="row">
            <div class="col-lg-6 col-md-12 col-sm-12 col-12">
              <div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-12">
                  <label for="full-name" class="form-label">Especialidade principal*</label>
                  <select class="form-select" aria-label="Default select example" id="specialty" placeholder="Selecione a especialidade">
                  <option selected>Selecione</option>
                  </select>
                </div>
              </div><br>
            
            <div class="row">
              <div class="col-lg-8 col-md-8 col-sm-10 col-10">
                <label for="value" class="form-label">Informe o preço da consulta*</label>
                <div class="input-group mb-3">
                    <span class="input-group-text" id="cash">R$</span>
                    <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)" id="value" placeholder="Valor">
                </div>    
              </div>
            </div>               

            <div class="row">
                <label for="value" class="form-label">Formas de pagamento da consulta*</label>
                <div class="d-flex justify-content-evenly">
                    <div class="container shadow mb-2 rounded ps-5 pt-2" id="cash-pay">
                      <div class="row">
                        <div class="col-lg-1 col-sm-1 col-2">
                          <div class="form-check">
                            <input class="form-check-input position-static" type="checkbox" id="blankCheckbox" value="option1" aria-label="...">
                          </div>
                        </div>
                        <div class="col-lg-11 col-sm-11 col-10">
                          <label class="form-label ps-4"><strong>Em dinheiro</strong></label>
                        </div>
                    </div>
                  </div>
                </div>
                
                <div class="d-flex flex-row">
                    <div class="container shadow mb-2 rounded ps-5 pt-2" id="pix">
                      <div class="row">
                        <div class="col-lg-1 col-sm-1 col-2">
                          <div class="form-check">
                            <input class="form-check-input position-static" type="checkbox" id="blankCheckbox" value="option1" aria-label="...">
                          </div>
                        </div>
                        <div class="col-lg-11 col-sm-11 col-10">
                          <label class="form-label ps-4"><strong>Pix</strong></label>
                        </div>
                      </div>
                  </div>
                </div>

                <div class="d-flex flex-column">
                    <div class="container shadow mb-2 rounded ps-5 pt-2" id="credit">
                      <div class="row">
                        <div class="col-lg-1 col-sm-1 col-2">
                          <div class="form-check">
                            <input class="form-check-input position-static" type="checkbox" v-model="checkBoxChecked" id="blankCheckbox" value="option1" aria-label="...">
                          </div>
                        </div>

                        <div class="col-lg-11 col-sm-11 col-10">
                          <label class="form-label ps-4 pb-1"><strong>Cartão de crédito</strong></label>
                          <br>
                          <div v-if="checkBoxChecked">
                            <label class="form-label ps-4">Parcelamento em</label>
                            <br/>

                            <div class="form-check mb-2 ps-5">
                              <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
                              <label class="form-check-label" for="flexRadioDefault1">
                                1x, sem juros
                              </label>
                            </div>
                            <div class="form-check mb-2 ps-5">
                              <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
                              <label class="form-check-label" for="flexRadioDefault2">
                                2x, sem juros
                              </label>
                            </div>
                              <div class="form-check mb-2 ps-5">
                              <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault3" checked>
                              <label class="form-check-label" for="flexRadioDefault3">
                                3x, sem juros
                              </label>
                            </div>
                          </div>
                        </div>
                    </div>
                  </div>
                </div>
            </div><br>

            <div class="row">
              <div class="col-lg-9 col-md-8 col-sm-8 col-8">
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>

              <div class="col-lg-3 col-md-4 col-sm-4 col-4">
                <label class="form-label" id="progress-label">2 de 2</label>
              </div>
            </div>

            <br/>

            <div class="row">
              <router-link to="/review">
                <div class="d-grid gap-2 col-12">
                  <button type="button" class="btn btn-primary">PRÓXIMO</button>
                </div>
              </router-link>
            </div>

            </div>
            <div class="col-lg-6">
              <div class="d-none d-lg-block">
                <img src="@/assets/desktop-pagina-2.png" class="img-fluid"/>
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


<script>
  export default {
    data() {
      return {
        checkBoxChecked: false
      }
    }
  }
</script>


<style>
#pix, #cash-pay, #credit {
  background-color: #F9F9F9;
}

#cash{
  background-color:#483698 ;
  color: white
}
</style>