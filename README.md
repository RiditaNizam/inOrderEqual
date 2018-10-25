public boolean inOrderEqual(int a, int b, int c, boolean equalOk) {
  
  if(equalOk == true){
    if (b >= a && c >= b){
      return true;
    }
  }
  
  else if(b > a && c > b){
    return true;
  }
  
  return false;
  
}
