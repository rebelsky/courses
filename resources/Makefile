default: subjects.ent

clean: 
	rm -rf subjects.ent

subjects.ent: subjects.var
	../tools/process-variables < $< > $@


