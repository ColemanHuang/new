# new

```js

function fn(n){
    let fi = [];
    fi[1] = 1;
    fi[2] = 1;
    for(let i = 3; i <= n; i++)
    {
        fi[i] = fi[i-1] + fi[i-2];
    }
    return fi[n];
}

let n = 10;
console.log(fn(n));
```

