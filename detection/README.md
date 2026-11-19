# Detection engineering

[Original YARA rule excerpt](yara-excerpt.txt) documents detection logic built from strings observed in the suspicious extension. It is a research rule, not production-ready detection. No current compilation, sample-detection benchmark or false-positive rate is claimed. The unused ID string does not constrain the condition and should be reviewed during tuning.

Future validation: use a benign corpus and controlled offline test fixtures, measure true and false positives, and version changes. No malware is distributed here.
