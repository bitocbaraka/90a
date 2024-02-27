# 90a
# TypeScript:
interface Shape {
  color: string;
}

function draw(shape: Shape) {
  console.log(`Drawing a ${shape.color} shape`);
}

let circle = { color: 'red' };
draw(circle);

