function buscarAula(codigoAula) {
  if (codigoAula === 'A-201') {
    return { edificio: 'Pabellón A', nivel: 2 };
  }
  return null;
}

module.exports = { buscarAula };