# Annotation-Suite-in-selenium
Annotation suite in selenium
package common;

import org.testng.annotations.AfterSuite;
import org.testng.annotations.BeforeSuite;

public class CommonDataSetup {
	
	@BeforeSuite
	public void datasetup() {
		System.out.println("Common data set-up");
	}
	
	@AfterSuite
	public void dataTeardown() {
		System.out.println("Common data clean-up");
	}

}

