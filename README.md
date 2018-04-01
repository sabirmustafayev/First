# First
CREATE TABLE `cars` (
  `Vin_Number` int(11) NOT NULL,
  `Model` char(1) DEFAULT NULL,
  `Body_Style` char(1) DEFAULT NULL,
  `Price` float DEFAULT NULL,
  `Year` int(11) DEFAULT NULL,
  PRIMARY KEY (`Vin_Number`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1
