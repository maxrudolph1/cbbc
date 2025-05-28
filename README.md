# Cryptographic Ingredient Pairing

This script creates random pairings between names and ingredients using cryptographic hashing.

## How it works:

1. Each name and ingredient is hashed using SHA-256
2. The hashed values are sorted independently
3. This creates a deterministic but seemingly random pairing
4. The original proposed ingredient is shown for reference

## Results:

| Name | Proposed Ingredient | Name Hash | Assigned Ingredient | Ingredient Hash |
|------|---------------------|-----------|------------|----------------|
| kason      | plantain                       | 0242c1c658 | brussel sprouts                | 107c375bca |
| pierriricardo | jalapeno                       | 1921ab2fd4 | plantain                       | 1ee989455e |
| siddhant   | semolina                       | 3477e5f0be | persimmon                      | 3054026fc6 |
| brett      | cabbage                        | 4cefa6b13a | jalapeno                       | 31ab3328ca |
| shankara   | tofu                           | 4ddc3c135b | pandan                         | 3c0ac08c28 |
| maxine     | lavender                       | 5487d9e0d1 | black fermented soy beans (dou chi) | 7c49e94b89 |
| celeste    | pandan                         | 5b0e1ceb31 | coffee                         | 9d89c25d93 |
| raines     | coffee                         | 82bc88d2b4 | tofu                           | a64bc3ba81 |
| max        | persimmon                      | 9baf3a4031 | lavender                       | ba4542a85b |
| stephanie  | cool ranch doritos             | a1df6dffb5 | semolina                       | cd36a162e5 |
| noah       | brussel sprouts                | cf3a3bbe33 | cabbage                        | ec574cf07e |
| andrew     | black fermented soy beans (dou chi) | d979885447 | cool ranch doritos             | fb4b590236 |
