# Lambda-Expression-


// without using lambda expression:

interface greet{

    void wish();

}

class student implements greet{

    public void wish(){

        System.out.println("Good morning... ");

    }

    public static void main(String... args){

        student t=new student();

        t.wish();

    }

}

// with using lambda expression:

interface bye{

    void say();

}

class teacher{

    public static void main(String... args){

        bye b=()-> System.out.println("take care.... bye");

        b.say();

    }

}
