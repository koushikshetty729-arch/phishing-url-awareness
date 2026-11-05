# Test Samples

These test cases use fictional or reserved example URL text.
The program checks text only and does not visit websites.

## Test 1: IP-address hostname
Input: http://192.0.2.10/account
Expected: IP-address warning and HTTP warning.
Observed: IP-address warning and HTTP warning.
Status: Passed

## Test 2: At symbol
Input: http://example.com@sample.invalid/login
Expected: @ symbol warning and HTTP warning.
Observed: @ symbol warning and HTTP warning.
Status: Passed

## Test 3: Many hostname segments
Input: https://a.b.c.d.e.example.invalid/path
Expected: Many hostname segments/subdomains warning.
Observed: Many hostname segments/subdomains warning.
Status: passed

## Test 4: Punycode marker
Input: https://xn--example.invalid/
Expected: Punycode-style hostname warning.
Observed: [put your actual result here]
Status: passed

## Test 5: Ordinary example URL
Input: https://www.example.com/login
Expected: No listed warning signs found.
Observed: No listed waring signs found. This does NOT prove safty.
Status: passed