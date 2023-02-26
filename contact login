package fluxgen;

import org.openqa.selenium.By;
import org.openqa.selenium.chrome.ChromeDriver;

public class ContactLogin {
	public static void main(String[] args) {
		try {
			   System.setProperty("webdriver.chrome.driver", "D:\\selenium files//chromedriver.exe");
			   ChromeDriver driver = new ChromeDriver();
				driver.get("https://fluxgen.com/");	
				driver.findElement(By.xpath("/html/body/div[4]/div/div[4]/i")).click();
				Thread.sleep(2000);
				driver.findElement(By.xpath("//a[@ href='https://fluxgen.com/contact/']")).click();
				Thread.sleep(2000);
				driver.findElement(By.id("nf-field-1")).sendKeys("channa");
				driver.findElement(By.name("nf-field-5")).sendKeys("maini");
				driver.findElement(By.name("nf-field-6")).sendKeys("tester");
				driver.findElement(By.name("email")).sendKeys("c9108120823@gmail.com");
				driver.findElement(By.name("nf-field-3")).sendKeys("the,and,there");
				driver.findElement(By.id("nf-field-7")).sendKeys("6");
				driver.findElement(By.name("nf-field-8")).sendKeys("4");
				driver.findElement(By.id("nf-field-4")).click();
		} catch (Exception e) {
			e.printStackTrace();
		}

	}

}
