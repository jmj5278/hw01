1. Title: 1985 Auto Imports Database

2. *[Learning Repository](https://archive.ics.uci.edu/ml/datasets/Automobile)
   *[The data description](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.names)
   *[Website of the data file](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data)

3.  Description:
      This data set was created by Jeffrey C. Shlimmer (Jeffrey.Schlimmer@a.gp.cs.cmu.edu) on 19 May 1987. 
      Jeffery used the several sources such as 
      (a) 1985 Model Import Car and Truck Specifications, 1985 Ward's
          Automotive Yearbook.
      (b) Personal Auto Manuals, Insurance Services Office, 160 Water
          Street, New York, NY 10038 
      (c) Insurance Collision Report, Insurance Institute for Highway
          Safety, Watergate 600, Washington, DC 20037
      

            
4. Number of Instances: 205

5. Number of Attributes: 26 total
   -- 12 quantitative variables
   -- 14 qualitative variables
   -- 15 continuous
   -- 1 integer
   -- 10 nominal

6. Attribute Information:     

     Attribute:             |   Attribute Range:
     ------------------        -----------------------------------------------
  a. symboling:                -3, -2, -1, 0, 1, 2, 3.
                               > The value of +3 represents the most risky auto 
                                 and -3 indicates the pretty safe auto 
                                 
  b. normalized-losses:        continuous from 65 to 256.
                               > It uses to compared to other cars
 
  c. make:                     alfa-romero, audi, bmw, chevrolet, dodge, honda,
                               isuzu, jaguar, mazda, mercedes-benz, mercury,
                               mitsubishi, nissan, peugot, plymouth, porsche,
                               renault, saab, subaru, toyota, volkswagen, volvo
                               >Names of auto companies 
                               
  d. fuel-type:                diesel, gas.
                               > Type of fuel
                              
  e. aspiration:               std, turbo.
                               > Type of aspration (std:standard)
                               
  f. num-of-doors:             four, two.
                               > Four doors | two doors
                               
  g. body-style:               hardtop, wagon, sedan, hatchback, convertible.
                               > Style of auto body 
  
  h. drive-wheels:             4wd, fwd, rwd.
                              >4wd(four wheels driving)
                               fwd(front wheels driving)
                               rwd(rear wheels driving)
  
  i. engine-location:          front, rear.
                               >Front(engine located in the front of auto)
                                rear(engine located in the rear of auto)
  
  j. wheel-base:               continuous from 86.6 120.9.
                               >Distance between front and rear wheeles
 
  k. length:                   continuous from 141.1 to 208.1.
                               >The length of auto
 
  l. width:                    continuous from 60.3 to 72.3.
                               >The width of auto
  
  m. height:                   continuous from 47.8 to 59.8.
                               >The height of auto
 
  n. curb-weight:              continuous from 1488 to 4066.
                               >The weight of an automobile without occupants or baggage
 
  o. engine-type:              dohc, dohcv, l, ohc, ohcf, ohcv, rotor.
                               >Type of engine
 
  p. num-of-cylinders:         eight, five, four, six, three, twelve, two.
                               >Number of cylinders
 
  q. engine-size:              continuous from 61 to 326.
                               >Size of engine
 
  r. fuel-system:              1bbl, 2bbl, 4bbl, idi, mfi, mpfi, spdi, spfi.
                               >System of fuel
 
  s. bore:                     continuous from 2.54 to 3.94.
                               >The size, in terms of diameter, of the cylinder in which a piston travels
                               
  t. stroke:                   continuous from 2.07 to 4.17.
                               >The distance travelled by the piston in each cycle
                               
  u. compression-ratio:        continuous from 7 to 23.
                               >the ratio of the maximum to minimum volume in the cylinder of 
                                an internal combustion engine
                               
  v. horsepower:               continuous from 48 to 288.
                               >the power of an engine measured 
                               
  w. peak-rpm:                 continuous from 4150 to 6600.
                               >Max rpm
 
  x. city-mpg:                 continuous from 13 to 49.
                               >One of mpg categories (City driving: go and stop situation) 
                               
  y. highway-mpg:              continuous from 16 to 54.
                               >One of mpg categores (Highway,long distance, travel)
 
  g. price:                    continuous from 5118 to 45400.
                               >Price of cars

7. Missing Attribute Values: Missing values are denoted as "?"
   
   Attribute #: |  Number of instances missing a value:
   -----------    --------------------------------------
   (#2)           |  41
   (#6)           |  2
   (#19)          |  4
   (#20)          |  4
   (#22)          |  2
   (#23)          |  2
   (#26)          |  4



