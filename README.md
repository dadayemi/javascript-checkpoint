# javascript-checkpoint
checkpoint
function bitwiseAND(a, b) {
    return a & b;
}

function bitwiseOR(a, b) {
    return a | b;
}

function bitwiseXOR(a, b) {
    return a ^ b;
}

console.log(bitwiseAND(7, 12)); // 4
console.log(bitwiseOR(7, 12));  // 15
console.log(bitwiseXOR(7, 12)); // 11

console.log((7).toString(2));  // "111"
console.log((12).toString(2)); // "1100"

function redundant(str) {
    return function () {
        return str;
    };
}
const result = getNotesDistribution([
  {
    name: "Steve",
    notes: [5, 5, 3, -1, 6]
  },
  {
    name: "John",
    notes: [3, 2, 5, 0, -3]
  }
]);

console.log(result);
// { 5: 3, 3: 2, 2: 1 }
