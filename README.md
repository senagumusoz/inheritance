# inheritance
Main

public class Main {

	public static void main(String[] args) {
	
		Student student=new Student();
		student.setMail("aaaaaa@gmail.com");
		student.setUserPassword("46549845");
		
		Instructor instructor = new Instructor();
		instructor.setLessonName("C#,JAVA");
		instructor.setId(000);
		
		User user= new User();
		user.setFirstName("sena");
		user.setLastName("bbbb");
		
		
		
		UserManager userManager = new UserManager();
		userManager.add(user);
		
		
		StudentManager studentManager = new StudentManager();
		studentManager.add(student);
		
		InstructorManager instructorManager = new InstructorManager();
		instructorManager.add(instructor);
	
	
	
	}

}
