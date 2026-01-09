# 3MF Secure Content extension keys

The "private_test.pem" and the "public_test.pem" provide the private and public testing keys used in the test suite.

The consumer under test should behave as if it is identified by the consumerid="test3mf01", even though for their production code could use a different consumerid. Secondly, the consumer under test should embed the test private key  and map this to keyid= “test3mfkek01” in order to be able to decrypt the test case’s encrypted content.

The consumerid and keyid noted above will be stored in the test case keystore part and these identifiers will be mapped to all encrypted content that the consumer under test is expected to decrypt unless noted otherwise.  
