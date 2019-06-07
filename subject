class Subject:
    def __init__(self):
        self.name = None
        self.abb = None
        self.teachers = []
        self.locations = []
        self.note = ""
        
    def setName(self, name):
        self.name = name
        
    def getName(self):
        return self.name
        
    def setAbb(self, abb):
        self.abb = abb
    
    def getAbb(self):
        return self.abb
    
    def addTeacher(self, teacher):
        self.teachers.append(teacher)
        
    def getListTeachers(self):
        return self.teachers
        
    def getObjectTeacher(self, nameTeacher):
        for teacher in self.teachers:
            if teacher.getName() == nameTeacher:
                return teacher
        
        return None
        
    def addLocation(self, location):
        self.locations.append(location)
        
    def getListLocations(self):
        return self.locations
        
    def getObjectLocation(self, nameLocation):
        for location in self.locations:
            if location.getName() == nameLocation:
                return location
       
       return None
        
    def setNote(self, note):
        self.note = note
        
    def getNote(self):
        return self.note
   
