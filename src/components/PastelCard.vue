<script>
export default {
  props: {
    description: String,
    imgSrc: String
  }
};
</script>

<template>
  <div class="card">
    <div class="card-header" style="text-align: center;">
      <h4>Pastel Armonia negativa</h4>
    </div>
    <div class="card-body">
      <div class="row">
        <!-- Image -->
        <div class="col-md-12">
          <div style="text-align: center;">
            <img :src="require('@/' + imgSrc)">
          </div>
        </div>
      </div>

      <div class="row">
        <!-- Metadata -->
        <div class="col-md-6">
          <span>No. personas: 4</span>
        </div>
        <div class="col-md-6">
          <span>Precio: $200</span>
        </div>
      </div><br/>

      <!-- Description -->
      <div class="row" style="width: 100%;">
        <p>{{description}}</p>
      </div><br/>

      <!-- Decorations -->
      <div class="row">
        <div class="col-md-12">
          <h5>Decoraciones disponibles</h5>
        </div>
        <div class="col-md-12 form-check">
          <label class="form-check-label">
            <input type="checkbox" class="form-check-input" value="">Lazo ($20)
          </label>
        </div>
        <div class="col-md-12 form-check">
          <label class="form-check-label">
            <input type="checkbox" class="form-check-input" value="">Caja madera ($50)
          </label>
        </div>
        <div class="col-md-12 form-check">
          <label class="form-check-label">
            <input type="checkbox" class="form-check-input" value="">Moño ($10)
          </label>
        </div>
      </div><br/>

      <!-- Combinaciones -->
      <div class="row">
        <div class="col-md-12">
          <h5>Combinaciones disponibles</h5>
        </div>
        <div class="col-md-12 form-check">
          <label class="form-check-label">
            <input type="checkbox" class="form-check-input" value="">Chocolate blanco
          </label>
        </div>
        <div class="col-md-12 form-check">
          <label class="form-check-label">
            <input type="checkbox" class="form-check-input" value="">Nutella
          </label>
        </div>
        <div class="col-md-12 form-check">
          <label class="form-check-label">
            <input type="checkbox" class="form-check-input" value="">Carlos V
          </label>
        </div>
      </div><br/>
    </div>
    <div class="card-footer" style="text-align: center; width: 100%;">
      <a href="./carrito.html" class="btn btn-primary" style="width: 80%">Comprar</a>
    </div>
  </div>
</template>
