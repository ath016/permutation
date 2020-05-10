// might have problems when dealing with arrays with different element types
// can handle arrays with elements that are the same value
Array.prototype.nextPermutation = function() {
  if(this.length < 2) return this;
  let max = this.reduce((a,b) => (b < a)? a: b);
  let size = this.filter((x) => x == max).length;

  // flip
  if(this.slice(this.length - size).every((x) => x == max)) {
    return this.slice(this.length - size)
      .concat(this.slice(0, this.length - size).nextPermutation());
  } // end of if

  // shift
  else {
    let index;
    this.forEach((x,i) => {if(x == max && i != this.length - 1 && this[i + 1] != max) index = i});
    let subArr = this.filter((x,i) => x == max && i >= index);
    let arr = this.filter((x,i) => x != max || i < index);
    return arr.slice(0, index + 1).concat(subArr, arr.slice(index + 1, this.length));
  } // end of else
} // end of next permutation
