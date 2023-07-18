# Dart-Map.
void main(){
  
  Map <String, String> positionMap={  
    
    "generalManger":"bing-hong",
    "humanResource":"xiao-tsai",
    "accouting":"xiao-mei"
  };
  
  //print (positionMap["generalManger"]);
  //插入新元素
  positionMap["partTime"]="xiao-black";
  //print (positionMap["partTime"]);
  
  for(String key in positionMap.keys){
    print("positionMap的key是 $key 時，value為 ${positionMap[key]}");
  }
}
