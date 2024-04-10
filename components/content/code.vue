<template>
    <pre><code tabindex="0">function wall(x, y, width, height) {
      return Matter.Bodies.rectangle(x, y, width, height, {
        chamfer: { radius: 10 }
      });
    }</code></pre>
</template>