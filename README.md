# pr.4
static int aa = 0;
    public void test(){
        long start = System.currentTimeMillis();

        for (int i=0;i<1000000000;i++){
            aa++;
        }
        long useTime = System.currentTimeMillis()-start;
        System.out.println("useTime:"+useTime);
    }
