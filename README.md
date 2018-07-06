# count-from-array
Code to count instances in array


    var  count = {};
    outputs.forEach(function(i) {
      count[i] = (count[i]||0) + 1;
    });
    console.log(count);

Remove duplicates using newset

Array.from(new Set(names));
