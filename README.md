# Dart-Map.
void main(){
  
  Map <String, String> positionMap={  
    
    "generalManger":"bing-hong",
    "humanResource":"xiao-tsai",
    "accouting":"xiao-mei"
  };
  
  //print (positionMap["generalManger"]);
  //插入單一新元素
  positionMap["partTime"]="xiao-black";
  //print (positionMap["partTime"]);
  
  //插入多個新元素
  positionMap.addAll({"worker":"sombody" , "intern":"Sean"});
 

  //可以用$去取值
  for(String key in positionMap.keys){
    print("positionMap的key是 $key 時，value為 ${positionMap[key]}");
  }
}
