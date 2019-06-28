# Metadata variable sizes

Setter and getter function sizes are given for when using variables inside metadata vectors.

| Variable type | Size, bytes | Getter size, bytes | Setter size, bytes | Size with getter, bytes | Size with setter and getter, bytes |
| ------------- | ----------- | ------------------ | ------------------ | ----------------------- | ---------------------------------- |
| int           | 4           | 22                 | 17                 | 26                      | 42                                 |
| float         | 4           | 22                 | 17                 | 26                      | 42                                 |
| bool          | 4           | 22                 | 17                 | 26                      | 42                                 |
| option        | 4           | 22                 | 17                 | 26                      | 42                                 |
| midiNote      | 5           | 23                 | 18                 | 28                      | 46                                 |
| colour        | 8           | 26                 | 21                 | 34                      | 55                                 |

