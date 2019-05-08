# try
try
<div id="spotxvideo"></div>
<div id="spotxbanner"></div>
<script type="text/javascript">
        function myAdDoneFunction(spotx_ad_found)  {
            if(spotx_ad_found)  {
                document.getElementById("spotxvideo").innerHTML = '[content to be played after ad display]';
            }
            else {
                document.getElementById("spotxvideo").innerHTML = '[backup ad request]';
            }
        };
</script>
<script type="text/javascript" src="//js.spotx.tv/easi/v1/85394.js" data-spotx_channel_id="85394" data-spotx_content_width="450" data-spotx_content_height="370" data-spotx_ad_done_function="myAdDoneFunction" data-spotx_content_container_id="spotxvideo" data-spotx_banner_container_id="spotxbanner" data-spotx_ad_unit="instream"></script>
