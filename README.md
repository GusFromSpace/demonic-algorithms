# demonic-algorithms

demoniC ports of [**TheAlgorithms/Python**](https://github.com/TheAlgorithms/Python)
— 44 algorithm translations, organized to mirror the upstream. Each is a
self-contained `.dmc` with **embedded numeric tests** (every port passes its own
`dmc test`, not just compiles).

## Run

```
dmc test ciphers/base16.dmc
```

## Index

### ciphers (12)
- `ciphers/affine_cipher.dmc` — Affine cipher ported from TheAlgorithms/Python cipher_affine_cipher.py
- `ciphers/baconian_cipher.dmc` — Baconian (Bacon's) cipher — ported from TheAlgorithms/Python
- `ciphers/base16.dmc` — base16 encode/decode ported from TheAlgorithms/Python cipher_base16.py
- `ciphers/base32.dmc` — Base32 encoding / decoding — ported from TheAlgorithms/Python cipher_base32.py
- `ciphers/base85.dmc` — Base85 (Ascii85) encode/decode
- `ciphers/decrypt_caesar_with_chi_squared.dmc` — Port of decrypt_caesar_with_chi_squared (TheAlgorithms/Python)
- `ciphers/morse_code.dmc` — Morse code encrypt/decrypt ported from TheAlgorithms/Python cipher_morse_code.py
- `ciphers/rot13.dmc` — ROT13 / Caesar cipher  (port of TheAlgorithms/Python ciphers/rot13.py)
- `ciphers/simple_keyword_cypher.dmc` — Simple keyword cypher ported from TheAlgorithms/Python
- `ciphers/trifid_cipher.dmc` — Trifid cipher ported from TheAlgorithms/Python cipher/trifid_cipher.py
- `ciphers/vigenere_cipher.dmc` — Vigenere cipher ported from TheAlgorithms/Python cipher_vigenere_cipher.py
- `ciphers/xor_cipher.dmc` — XOR-cipher (port of TheAlgorithms/Python cipher/xor_cipher.py)

### hashes (6)
- `hashes/emitter_converter.dmc` — Hamming-code emitter/converter, ported from TheAlgorithms/Python emitter_converter.py
- `hashes/fletcher16.dmc` — Fletcher-16 checksum (position-dependent), ported from TheAlgorithms/Python.
- `hashes/hamming_code.dmc` — Hamming code encode/decode, ported from TheAlgorithms/Python hash_hamming_code.py
- `hashes/luhn.dmc` — Luhn algorithm validation, ported from TheAlgorithms/Python hashes/luhn.py
- `hashes/receptor_converter.dmc` — Hamming receptor/converter port from TheAlgorithms/Python receptor_converter.py
- `hashes/sdbm.dmc` — sdbm hash (64-bit masked variant of the public-domain sdbm string hash).

### sorts (8)
- `sorts/bubble_sort.dmc` — Faithful port of TheAlgorithms/Python bubble_sort (iterative + recursive).
- `sorts/cocktail_shaker_sort.dmc` — cocktail shaker sort, ported from TheAlgorithms/Python
- `sorts/comb_sort.dmc` — Comb sort: improves on bubble sort by using a shrinking gap.
- `sorts/counting_sort_string.dmc` — Port of counting_sort_string.py (TheAlgorithms)
- `sorts/fischer_yates_shuffle.dmc` — Fisher-Yates shuffle ported from TheAlgorithms/Python
- `sorts/insertion_sort.dmc` — insertion sort over a fixed-size f32 tensor, ascending
- `sorts/pancake_sort.dmc` — Pancake sort, ported from TheAlgorithms/Python sorts/pancake_sort.py
- `sorts/shell_sort.dmc` — Shell sort (Marcin Ciura's gap sequence)

### searches (3)
- `searches/interpolation_search.dmc` — Port of TheAlgorithms/Python search/interpolation_search.py
- `searches/jump_search.dmc` — Jump search over a sorted int array (TheAlgorithms/Python search_jump_search).
- `searches/ternary_search.dmc` — Ternary search (divide-and-conquer into 3 parts) — ported from

### dynamic programming (6)
- `dynamic_programming/edit_distance.dmc` — Edit distance (Levenshtein), bottom-up DP.
- `dynamic_programming/longest_increasing_subsequence.dmc` — Longest increasing subsequence (returns the actual subsequence).
- `dynamic_programming/matrix_chain_order.dmc` — Matrix chain multiplication: minimum number of scalar multiplications.
- `dynamic_programming/max_subarray_sum.dmc` — Kadane's algorithm — maximum subarray sum.
- `dynamic_programming/subset_generation.dmc` — Port of dp_subset_generation.subset_combinations (TheAlgorithms/Python)
- `dynamic_programming/word_break.dmc` — Word Break (LeetCode): can `string` be segmented into a sequence of `words`?

### data structures (2)
- `data_structures/lru_cache.dmc` — Array-backed LRU cache (algorithm port of TheAlgorithms/Python other/lru_cache.py).
- `data_structures/sparse_table.dmc` — Range Minimum Query via a sparse table (ported from TheAlgorithms/Python

### conversions (6)
- `conversions/length_conversion.dmc` — Length unit conversion (ported from TheAlgorithms/Python conv_length_conversion.py)
- `conversions/octal_to_decimal.dmc` — Convert an octal string to its decimal equivalent.
- `conversions/pressure_conversions.dmc` — Pressure unit conversion ported from TheAlgorithms/Python conv_pressure_conversions.py
- `conversions/speed_conversions.dmc` — Convert speed units (port of TheAlgorithms convert_speed)
- `conversions/temperature_conversions.dmc` — Temperature conversions, ported from TheAlgorithms/Python
- `conversions/weight_conversion.dmc` — Port of TheAlgorithms/Python weight_conversion.

### math (1)
- `math/gauss_easter.dmc` — Gauss's Easter algorithm (Computus) — Gregorian Easter date for a given year.

## License & attribution

demoniC ports under the **MIT License**, matching the upstream — see
[LICENSE](LICENSE) and [NOTICE](NOTICE). Original algorithms © 2016-2022
TheAlgorithms and contributors. Parent-pure: only TheAlgorithms translations,
nothing else added.

