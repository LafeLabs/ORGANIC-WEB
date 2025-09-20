<?php
//$baseurl = "https://raw.githubusercontent.com/lafefspietz/organic-web/refs/heads/main/JPA/data091825-base/scan3/trace0.s2p";

//copy("https://raw.githubusercontent.com/lafefspietz/organic-web/refs/heads/main/JPA/data091825-base/scan3/trace0.s2p","ampdata/trace0.s2p");

for ($i = 1; $i < 100; $i++) {
///    echo 'trace'.$i.'.s2p<p>';
    copy("https://raw.githubusercontent.com/lafefspietz/organic-web/refs/heads/main/JPA/data091825-base/scan3/trace".$i.".s2p","ampdata/trace".$i.".s2p");
}

?>
<a href = "edit-php-files.html">edit php</a>
<style>
</style>
