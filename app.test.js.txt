const { buscarAula } = require('./index');

test('Encuentra el aula A-201', () => {
  const aula = buscarAula('A-201');
  expect(aula).not.toBeNull();
  expect(aula.edificio).toBe('Pabellón A');
});
