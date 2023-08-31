```python
class Attributes(IMNIGHT):
	@staticmethod
	def contact() -> tuple:
	    phone = "13643584702"
	    email = "night66688@gmail.com"
	    
	    return email, phone
	
	@staticmethod
	def life() -> tuple:
		age = 24
		
		return age
	
	@staticmethod
	def coding() -> tuple:
		langs = {
			'expert': ['python'],
			'intermediate': ['go', 'js'],
			'learning': ['java']
		}
		specialities  = ['web/app engineering', 'fullstack']
		environnement = ['vscode']
		
		return langs, specialities, environnement
