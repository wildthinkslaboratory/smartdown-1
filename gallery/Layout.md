### Non-linear Layouts

Blah

#### Simple Example where HTML is injected

#### --outlinebox outer

#### --outlinebox left

**Definition 1.0**
For sets $A$ and $B$ the *Cartesian product* or *cross product*, of $A$ and $B$ is denoted by $A \times B$ and equals
$$\{(a,b) \, | \, a \in A, \, b \in B \}$$

An element $(a,b)$ of $A \times B$ is called an *ordered pair*.

#### --outlinebox


#### --outlinebox middle

**Definition 1.0**
For sets $A$ and $B$ the *Cartesian product* or *cross product*, of $A$ and $B$ is denoted by $A \times B$ and equals
$$\{(a,b) \, | \, a \in A, \, b \in B \}$$

An element $(a,b)$ of $A \times B$ is called an *ordered pair*.

#### --outlinebox


#### --outlinebox right

**Definition 1.0**
For sets $A$ and $B$ the *Cartesian product* or *cross product*, of $A$ and $B$ is denoted by $A \times B$ and equals
$$\{(a,b) \, | \, a \in A, \, b \in B \}$$

An element $(a,b)$ of $A \times B$ is called an *ordered pair*.


#### --outlinebox
#### --outlinebox


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Here is a triptych: Here is a [](:&divx). Isn't it cool? Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


```javascript /playable/autoplay

smartdown.importCssCode(
`

.outer {
  border: 5px solid red;
  text-align: center;
}

.left {
  border: 1px solid green;
}

.middle {
  border: 1px solid cyan;
}

.right {
  border: 1px solid magenta;
}

@media (min-width: 800px) {
  .outer {
    border: 5px solid pink;
  }

  .left {
    width: 30%;
    display: inline-block;
  }

  .middle {
    width: 30%;
    display: inline-block;
  }

  .right {
    width: 30%;
    display: inline-block;
  }
}
`);

const targetId = 'inline-target-divx';  // this.div.id;
const targetDiv = document.getElementById(targetId);
targetDiv.innerHTML =
`
<div class="outer">
  <div class="left">
    <h1>Left</h1>
  </div>

  <div class="middle">
    <h1>Middle</h1>
  </div>

  <div class="right">
    <h1>Right</h1>
  </div>
</div>
`;


const outer = document.getElementById('outer');
const left = document.getElementById('left');
const middle = document.getElementById('middle');
const right = document.getElementById('right');
console.log('left', left);

// const left = document.querySelectorAll(`#${targetId} .left`)[0];
// const middle = document.querySelectorAll(`#${targetId} .middle`)[0];
// const right = document.querySelectorAll(`#${targetId} .right`)[0];

outer.classList.add('outer');
left.classList.add('left');
middle.classList.add('middle');
right.classList.add('right');

```


---

[Back to Home](:@Home)

