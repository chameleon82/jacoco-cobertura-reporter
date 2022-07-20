# jacoco-cobertura-reporter
Cobertura format reporter for jacoco


Example of output expected
```xml
<?xml version='1.0' encoding='UTF-8'?>
<!DOCTYPE coverage SYSTEM 'http://cobertura.sourceforge.net/xml/coverage-04.dtd'>
<coverage line-rate="0.8571428571428571" branch-rate="0.5" lines-covered="6" lines-valid="7" branches-covered="1" branches-valid="2" function-rate="1.0" functions-covered="2" functions-valid="2" complexity="0.0" timestamp="1573053861" version="gcovr 5.1">
  <sources>
    <source>.</source>
  </sources>
  <packages>
    <package name="" line-rate="0.8571428571428571" branch-rate="0.5" function-rate="1.0" complexity="0.0">
      <classes>
        <class name="example_cpp" filename="example.cpp" line-rate="0.8571428571428571" branch-rate="0.5" complexity="0.0">
          <methods/>
          <lines>
            <line number="3" hits="1" branch="false"/>
            <line number="5" hits="1" branch="true" condition-coverage="50% (1/2)">
              <conditions>
                <condition number="0" type="jump" coverage="50%"/>
              </conditions>
            </line>
            <line number="7" hits="0" branch="false"/>
            <line number="11" hits="1" branch="false"/>
            <line number="15" hits="1" branch="false"/>
            <line number="17" hits="1" branch="false"/>
            <line number="19" hits="1" branch="false"/>
          </lines>
        </class>
      </classes>
    </package>
  </packages>
</coverage>
```
