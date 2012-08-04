1. Escaping asterisks and underscores:
  - \**this text should not be strong but it should be emphasized\**
  - \__this text should not be strong but it should be emphasized\__

2. Nesting of emphases and strongs:
  - **_this text should be both strong and emphasized_**
  - __*this text should be both strong and emphasized*__

3. Mailto action doesn't work: <test@test.com> (a path is prepended to the address).

4. Handling and color of HTML comments. <!-- test, _test_ test -->

5. Coloring dosen't always refresh immediately (it's probably due to multiline regexes).

6. Indented paragraphs inside lists should not be treated as code:

    This should not be treated
    as code.
