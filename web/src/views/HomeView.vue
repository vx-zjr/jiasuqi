<div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front" />
    <div class="flip-card-back" />
  </div>
</div>

<style>
.flip-card {
  perspective: 1000px;
}
.flip-card-inner {
  transition: transform 0.6s;
  transform-style: preserve-3d;
}
.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}
</style> 