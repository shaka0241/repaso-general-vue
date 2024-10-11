<template>
    <h2>Gestion de estudiantes</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Nombre</th>
                <th>Edad</th>
                <th>Estado</th>
                <th>Califaciones</th>
                <th>Cambiar estado</th>
            </tr>
        </thead>
    </table>
</template>

<script>
export default {
  data() {
    return {
      estudiantes: [
        {
          nombre: 'Juan Pérez',
          edad: 20,
          activo: true,
          calificaciones: {
            matematicas: 7,
            ciencias: 8,
            historia: 6
          }
        },
        {
          nombre: 'Ana Gómez',
          edad: 22,
          activo: false,
          calificaciones: {
            matematicas: 9,
            ciencias: 9,
            historia: 8
          }
        },
        {
          nombre: 'Carlos Mendoza',
          edad: 21,
          activo: true,
          calificaciones: {
            matematicas: 6,
            ciencias: 5,
            historia: 7
          }
        }
      ]
    };
  }
};
</script>

<style scoped>
.inactivo {
    background-color: #f8d7da;
}
</style>