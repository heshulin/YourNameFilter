# YourNameFilter
你的名字版滤镜

调用方法如下

public class Main {

    public static  void main(String []agr0)
    
    {
    
        YournameFilter yournameFilter = new YournameFilter();
        
        try {
        
            yournameFilter.pullPhoto("E:/e.jpg");
            
        } catch (Exception e) {
        
            e.printStackTrace();
            
        }
        
        System.out.println(yournameFilter.getPhotoUrl());
        
    }   
}

yournameFilter.pullPhoto("E:/e.jpg")参数为一个图片的真实路径

yournameFilter.getPhotoUrl()返回值为一个URL

