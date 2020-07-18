# md5encoder

> MD5 Password Encoder & Decoder


## php md5 encoder for 4 digit pin

**It only supports number and pin must contains 4 digit integer**

> Tools
- PHP

**PHP SAMPLE**

```PHP

for($i=0; $i<strlen($txt); $i++ ) {
        $ch1 = $txt[$i];   


    for($j=0; $j<strlen($txt); $j++ ) {
          $ch2 = $txt[$j];

          for($k=0; $k<strlen($txt); $k++ ) {
               $ch3 = $txt[$k]; 

             for($l=0; $l<strlen($txt); $l++ ) {
                $ch4 = $txt[$l]; 

               $try = $ch1.$ch2.$ch3.$ch4;

               $check = hash('md5', $try);
                 if ( $check == $md5 ) {
                    $goodtext = $try;
                    break;
                 }
} 

```

### Saikat Roy

> Email: njmsaikat@gmail.com

> Personal Portfolio: https://njmsaikat.github.io/saikat/

> Linked In Profile: https://www.linkedin.com/in/njmsaikat/
