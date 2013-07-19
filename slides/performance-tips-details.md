# Performance <x>Tips</x>

- Use hardware accelerated animation <x>wherever possible</x>  
<small>Avoid jQuery's "animate()" and use CSS Transitions</small>
- Use CSS hardware acceleration <x>sparingly</x>  
<small>Put too much on the GPU and tearing and you can run out of GPU memory quickly</small>
- <x>DO NOT</x> use complex nested DOM structures, box-shadows, heavy gradients and other <x>performance killers</x>