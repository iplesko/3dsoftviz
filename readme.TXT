Vytvorenie nov�ho grafu:
	-treba pou�i� met�dy v triede Graph, addNode, addEdge a pod.

Spustenie Layoutovacieho algoritmu
	-spravil som vzorovy priklad, v triede Example sa vytvara vzorovy graf
	-spustanie je v metode AppCore::Core::Core(QApplication * app)
	-ukoncenie nastane v metode FRAlgorithm::Run, ked metoda iterate vrati false

--------------------------------------------------------------------------------------------
Preveden� �pravy:
	-odstr�nen� moduly a triedy, ktor� sl��ili len na zobrazovanie, GUI a pod.
	-odstr�nen� referencie na OSG, v��inou boli len zakomentovan�
	-n�hrada za triedu OSG Vec3f, Vec3 a Vec3d je trieda Data::Vector, prebran� z OSG Vec3f
--------------------------------------------------------------------------------------------