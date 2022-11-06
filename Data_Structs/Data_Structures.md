Intro
  What Are Data Structs?
    - elementary particles of algos, woven into the fabric of comp sci 
    - solutions for the manipulation of Data

  Complexity Analysis 
    - the process of determining how efficient an algo is 
    - determined in Space and Time Complexity
    - Time Complexity => a measure of how "fast " an algo is, expressed in BigO 
    - Space Complexity => measure of how much memory an alga takes to run, expressed in BigO

  Memory 
    - Bit => short for binary digit, fundamental unit of info, represents 1 or 0 
    - Byte => a group of 8 bits, a single byte can be up to 256 data values (2^8)
    - Fixed-Width Integer => represented by a fixed amount, like 32 bit or 64 bit
                             regardless of how large an int is, its Fixed-Width
                             Integer is made of constant number of bits, i.e. no 
                             matter how small, even if its val is 1, it will still
                             take up 64 bits (memory hog)
    - Memory, the amount of memory is bounded, making it valuable to limit how much memory
      an algo takes up

  Big O Notation
    - used time and space Complexity to describe an algo
    - denotes the sizes of inputs to algos:
      => Constant: O(1)
          - as n increases, the time of O(1) is constant
      => Logarithmic: O(log(n))
          - see Logarithmic Section
      => Linear: O(n)
          - as n increases, the time of the algo increases linearly 
      => Log-Linear: O(nlog(n))
      => Quadratic: O(n^2)
      => Cubic O(n^3)
      => Exponential: O(2^n)
      => Factorial: O(n!)
    - In coding interviews, BigO usually describes worst case Complexity
    - Techniques of how to determine time complexity:
      => when writing the algo, if it contains mutiple algos then take the worst case to
      describe the BigO for the whole algo

  Logarithm
    - math concept that is widely used in comp sci, defined by:
        log ,subB(x) = y if and only if b^y = x
