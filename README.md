# HBUrlConnection

How to use :

//put key and value using HashMap

	final HashMap<String, String> map = new HashMap<String, String>();
	map.put("user_name", userName);
	map.put("password", password);

//set to listener

	urlConnection.listener= this;

//fire it away

	urlConnection.send(MobileServicesAPI, urlConnection.convertToParams(map));
