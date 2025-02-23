<template>
    <div>
      <!-- Modal -->
      <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h1 class="modal-title fs-5" id="exampleModalLabel">Cadastre-se</h1>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              <div class="d-grid gap-2">
                <button class="btn btn-primary" type="button">Receber as nossas ofertas</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>
  
<script>
  export default {
    mounted() {
      // Mostra o modal sempre que a página for carregada ou recarregada
      const myModal = new bootstrap.Modal(document.getElementById('exampleModal'));
      myModal.show();
    }
  }
</script>
  