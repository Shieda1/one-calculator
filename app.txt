// https://www.omnicalculator.com/math/ceiling-function

const v1 =  document.getElementById('v1');
const btn = document.getElementById('btn');
const result = document.getElementById('result');

btn.addEventListener('click', function() {
  
    result.textContent = `Ceiling of x = ${computeSpecificVolume()}`;
})

// calculation

function computeSpecificVolume() {
  return Math.ceil(Number(v1.value));
}