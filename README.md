# JSONlib
A simple java json library.


# Use
Designed to be used as simple as possible:

    String jsonstr = "...";
    JSONObject jobj = new JSONObject(jsonstr);
		
    String valueA = jobj.getString("keyA");
    Boolean valueB = jobj.getBoolean("keyB");
    Integer valueC = jobj.getInt("keyC");
    Long valueD = jobj.getLong("keyD");
    
    JSONOBject valueE = jobj.getJSONObject("keyE");
    JSONArray jarray = jobj.getJSONArray("keyF");
    
    for (int i = 0; i < jarray.size(); ++i) {
        String vA = jarray.getString(i);
        Boolean vb = jarray.getBoolean(i);
        Integer vb = jarray.getInt(i);
        JSONOBject valueE = jobj.getJSONObject(i);
    }
    
    
    


# Known projects which use this lib:
* Autosave (https://collicalex.github.io/AutoSave/)
