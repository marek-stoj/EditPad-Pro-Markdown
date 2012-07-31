1. Escaping asterisks and underscores:

  - \**this text should not be strong but it should be emphasized\**
  - \__this text should not be strong but it should be emphasized\__
  - \***this text should not be emphasized but is should be strong**\*

2. Nesting of emphases and strongs:

  - **_this text should be both strong and emphasized_**
  - __*this text should be both strong and emphasized*__

3. Mailto action doesn't work: <test@test.com> (a path is prepended to the address).

4. Process multiline matches paragraph-wise? See points 1 and 2 above -- emphasis "leaks" between them.

5. Markdown coloring should be disabled in **block-level** HTML elements, eg.:
   
   <div>There shold be **no Markdown syntax coloring** here.</div>
