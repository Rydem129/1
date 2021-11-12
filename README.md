# 1 void DrawGraf(){
glLineWidth(1.66);
glBegin(GL_LINES);
glColor3f(0,0,0);
glVertex2f(0,1000);
glVertex2f(0,-1000);

glVertex2f(-1000,0);
glVertex2f(1000,0);
glEnd();

    glBegin(GL_LINE_STRIP);
    //glColor3f(1,0,0);
    for (float i = -100;i<200;i+=0.1){
    glColor3f(i/5,i+8,0);
    //glVertex2f(100*sin(15*i*M_PI/180+20),200*sin(1*i*M_PI/180+13));
    //glVertex2f(i,exp(i+3)/tan(i));
    //glVertex2f(i, pow((i+sin(i)),3));
    //glVertex2f(i, -0.23 * pow(i,2) + i );
    //glVertex2f(i, sqrt(  (1 + 3 * i)/2 + 3 * i ) );
    //glVertex2f(i, pow( (5+ 4 * i) ,2) +8 * i + cos(21 * i +10) );
    glEnd();
}
