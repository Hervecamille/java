"Special Arrays"
  function isSpecialArray(arr){
  for(let i= 0; i< arr.length; i++)
    if(arr[i] % 2 !=0)
    {return false}
  }
  for(let i= 1; j< arr.length; j++){
    if(arr[j] % 2 !=0)
    {return false}
  }
  return true
  }

"How much is true"
  function countTrue(arr){
    let count = 0;
      for(let element of arr)
        if(element === true)
          count++
  reyurn count  
  }

"Array multiple"
  let output = []
  let multiple = 0
  for(i = 1; i < length + 1; i++){
    multiple = num*i
    output.push(multiple)
  }
  return output

  "convert key, value in an object to array"
    function objectToArray(obj){
      var r = [];
      for(var i in obj){
        r.push([i, obj[i]]);
      }
      return r;
    }

    "sum of cubes"
      function sumOfCubes(nms){
        return nms.reduce((a,v)=> a+(v*v*v),0)
      }

    "is the number symmetrical"
      function isSymmetrical(num){
        const arr = num.toString().split('')
      return arr.join('') == arr.reverse().join('')
      }
