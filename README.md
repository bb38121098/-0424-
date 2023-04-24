# -0424-
-- Your code here!
fact[] = 1
fact (n:ns) = n * fact (ns)

main = do
    print $ fact[2,3,4]
