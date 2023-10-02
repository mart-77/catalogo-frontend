<template>
  <q-page padding>
    <div class="q-pa-md">
      <q-table :icon="local_shipping" title="Producto" :rows="rows" :columns="columns" row-key="name"
        :no-data-label="'Sin datos'" :loading-label="'Cargando...'" />
    </div>
  </q-page>
</template>

<script>
export default {
  setup() {
    const columns = [
      //{ name: 'calories', align: 'center', label: 'Calories', field: 'calories', sortable: true }
    ]
    const rows = []
    return {
      columns,
      rows
    }
  }

}
</script>
