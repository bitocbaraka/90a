# 90a
# TypeScript:
interface shape {
  color: string;
}

function draw(shape: Shape) {
  console.log(`Drawing a ${shape.color} shape`);
}

let circle = { color: 'blue' };
draw(circle);

