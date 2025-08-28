# SQL & Database Systems Projects

## 🗄️ Database Design & Management

### Project Overview
This section showcases my academic work in database systems, SQL query optimization, and data management. The projects demonstrate proficiency in database design principles, complex query writing, and system analysis.

### Academic Course
- **Course**: ISYS 864 - Database Systems
- **Focus**: Advanced database design, SQL optimization, and system architecture
- **Institution**: San Francisco State University

### Key Projects

#### 📊 Database Systems Final Project
**Files**: 
- `ISYS_864_Database_Systems_Final_Report.pdf` - Comprehensive project analysis
- `ISYS_864_Database_Systems_Final_Presentation.pdf` - Executive presentation

**Project Highlights**:
- **Database Design**: Entity-relationship modeling and normalization
- **Query Optimization**: Performance tuning and index strategies
- **System Architecture**: Scalable database solution design
- **Data Integration**: Multi-source data consolidation

### Technical Skills Demonstrated

#### 🔧 Database Technologies
- **SQL**: Complex queries, joins, subqueries, and stored procedures
- **Database Design**: ER modeling, normalization, and schema optimization
- **Performance Tuning**: Index optimization and query performance analysis
- **Data Warehousing**: ETL processes and dimensional modeling

#### 📈 Business Applications
- **Data Analytics**: Business intelligence and reporting solutions
- **System Integration**: Cross-platform data synchronization
- **Security**: Database security and access control implementation
- **Scalability**: Design for high-volume data processing

### Key Learning Outcomes

1. **Advanced SQL Proficiency**
   - Complex query construction and optimization
   - Window functions and advanced analytics
   - Stored procedures and database programming

2. **Database Architecture**
   - Relational database design principles
   - ACID properties and transaction management
   - Backup and recovery strategies

3. **Performance Optimization**
   - Query execution plan analysis
   - Index design and maintenance
   - Database tuning methodologies

4. **Business Intelligence**
   - Data warehouse design patterns
   - OLAP vs OLTP system design
   - Reporting and analytics solutions

### Real-World Applications

- **Enterprise Systems**: Scalable database solutions for business operations
- **Data Analytics**: Foundation for business intelligence and reporting
- **System Integration**: Database-driven application development
- **Performance Optimization**: Cost-effective data processing solutions

### Technical Competencies

```sql
-- Example of advanced SQL techniques covered:
WITH performance_metrics AS (
    SELECT 
        department_id,
        employee_id,
        salary,
        ROW_NUMBER() OVER (PARTITION BY department_id ORDER BY salary DESC) as rank
    FROM employees
)
SELECT 
    d.department_name,
    pm.employee_id,
    pm.salary,
    AVG(pm.salary) OVER (PARTITION BY pm.department_id) as dept_avg
FROM performance_metrics pm
JOIN departments d ON pm.department_id = d.department_id
WHERE pm.rank <= 3;
```

### Future Applications

This database systems foundation supports:
- **Data Engineering**: Pipeline design and data architecture
- **Analytics Platforms**: Scalable data processing solutions
- **Enterprise Applications**: Robust backend system development
- **Cloud Migration**: Modern database technology adoption

---

*These projects demonstrate comprehensive understanding of database systems from theoretical foundations to practical implementation, preparing for roles in data engineering, database administration, and system architecture.*