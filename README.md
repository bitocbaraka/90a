# 90a
# TypeScript:
interface shape {
  Color: string/
}

function draw(shape: Shape) {
  console.log(`Drawing a ${shape.color} shape`);
}

let circle = { color: 'green' };
draw(circle);

