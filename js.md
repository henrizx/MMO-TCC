// ... (seu código JavaScript existente) ...

const btnCadastrar = document.getElementById('btn-cadastrar');
const btnFechar = document.getElementById('btn-fechar');
const popup = document.getElementById('popup');
const cadastroForm = document.getElementById('cadastro-form');

btnCadastrar.addEventListener('click', () => {
  popup.style.display = 'flex';
});

btnFechar.addEventListener('click', () => {
  popup.style.display = 'none';
});

cadastroForm.addEventListener('submit', (event) => {
  // ... (seu código JavaScript existente) ...
});

function isValidEmail(email) {
  // ... (seu código JavaScript existente) ...
}

function isValidPassword(password) {
  // ... (seu código JavaScript existente) ...
}

function isValidCpfCnpj(cpfCnpj) {
  // ... (seu código JavaScript existente) ...
}

function isValidNumeroCelular(numeroCelular) {
  // ... (seu código JavaScript existente) ...
}
