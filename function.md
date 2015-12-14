###functions
function halloween(name){ <br>
  return 'hello ' + name; <br>
} <br>
document.getElementById('demo').innerHTML = halloween('terry'); <br>

var xmas = function(named){ <br>
  document.getElementById('demo2').innerHTML = 'bonjour ' + named; <br>
}; <br>
xmas('june'); <br>
