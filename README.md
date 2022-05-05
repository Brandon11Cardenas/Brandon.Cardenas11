# Brandon.Cardenas11
use hospital;
DELIMITER //

CREATE PROCEDURE GetAllhospital()
BEGIN
     SELECT * FROM citas;
     END //
DELIMITER ;
