    #php-excel-reader-php8

    #Original code from:
    https://github.com/nuovo/spreadsheet-reader


    #work with php >= 8
    
    #Suitable for Arabic language


    #example
    
    


    require_once('php-excel-reader-php8/excel_reader2.php');

    require_once('php-excel-reader-php8/SpreadsheetReader.php');



    $Spreadsheet = new SpreadsheetReader($xls_path);


    //$Sheets = $Spreadsheet -> Sheets();


    $Spreadsheet -> ChangeSheet(0);



    foreach ($Spreadsheet as $key => $row) {

        $xls_column_a = $row[0];
        
        $xls_column_b = $row[1];
	
        
        $xls_column_c = $row[2];

	//......................

    }

    //......................

