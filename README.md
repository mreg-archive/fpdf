fpdf
====

Unofficial PSR-0 compliant version of the FPDF library


This is version 1.7 with some minor changes:

* the library is namespaced in fpdf. To create instance use

    $fpdf = new \fpdf\FPDF();

* directory structure follow the PSR-0 standard with src/ as root

* on error a RuntimeException is thrown instead on lib dramatically dying 

* constructor is renamed '__construct' instead of 'FPDF'
