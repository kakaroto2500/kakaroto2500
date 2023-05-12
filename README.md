package Perfil_github;

public class Oliver_Programmer {

		public Oliver_Programmer(int quality, boolean professionalism) {
			
			
			this.LOT_OF_CUALITY = quality;
			
			this.VERY_PROFESSIONAL = professionalism;
			
			
			
		}
		
		final private int LOT_OF_CUALITY;
		
		final private boolean VERY_PROFESSIONAL;
}


	class About extends Oliver_Programmer{

		public About(int quality, boolean professionalism, boolean html, boolean css, boolean JavaScript, int Java, double SQL) {
			super(quality, professionalism);
			
			this.HTML = html;
			
			this.BOOSTRAP = css;
			
			this.ANGULAR = JavaScript;
			
			this.REACT = JavaScript;
			
			this.SPRING = Java;
			
			this.NET = SQL;
			
			

		}
		
		private boolean HTML;
		
		private boolean BOOSTRAP;
		
		private boolean REACT;
		
		private boolean ANGULAR;
		
		private int SPRING;
		
		private double NET;
		
		
		
		public String getAllSkills() {
			
			return " A VERY GOOD FULL SATCK PROGRAMMER";
		}
		
		
	}

