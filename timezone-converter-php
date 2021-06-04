protected function get_timemillizone_date($timezone_id)
  {
        date_default_timezone_set($timezone_id);
        $availdate = date('Y-m-d');
        $stamp = strtotime($availdate); // get current date timestamp
        $currenttimemill = $stamp * 1000;
        return $currenttimemill;
 }
 
 $timezone_id = "Asia/Kolkata";
 $RETURN_DATA = $this->get_timemillizone_date($timezone_id);
 echo $RETURN_DATA;
