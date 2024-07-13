# zcnes-single-step-tests

These tests are kept separate from the other ZCNES
[tests](https://github.com/zachcmadsen/zcnes-tests) because they take up a lot
of space. I can choose when to pay the extra download time, e.g., during local
development and not CI.

The tests were encoded in [JSON](https://github.com/SingleStepTests/65x02). I
converted them to a [binary](https://github.com/felixguendling/cista) format to
speed up deserialization.