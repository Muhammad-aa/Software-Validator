# Software-Validator
This is a python script that validates the integrity of a software after download. This is useful in protecting against data modification by hackers.
Sometimes, we might be connected to Wi-Fi networks that are vulnerable to Man-in-the-middle-attacks or even be victims of social engineering.
This script helps us validate the integrity of any software we download using the hash value provided by the vendors.

Usage: python hash_cli.py -f [File/software to verify] --hash [Hash value]
