# ABLESTACK-Skydive

ABLESTACK-Skydive�� �ǽð� ��Ʈ��ũ �������� �� �������� �м���ν� ��Ʈ��ũ �����󿡼� �Ͼ�� ���� ���������� ������ �� �ֵ��� ������ �����ϴ� ���� ��ǥ�� �մϴ�.


ABLESTACK-Skydive Analyzer�� Agent�κ��� ��Ʈ��ũ �̺�Ʈ�� �����Ͽ� �Ʒ��� ���� ��Ʈ��ũ ���������� ǥ���մϴ�.<br/><br/>
![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-ui-main.png?raw=true)

## Key features

* ��Ʈ��ũ �������� �� flows ĸó
* VM ������ ����
* ����ġ ���� ����
* ��Ÿ������ �˻��� ���� ���̶���Ʈ ���


## Tutorials

 - �����ϱ�
   - �� UI
     - ABLESTACK-Skydive�� ��ġ�� �Ϸ�� �� ��Ʈ 8082�� ���� Web UI�� ����� �� �ֽ��ϴ�. �� ���������� http://{mold�� ipv4 �ּ�}:8082�� �����ϸ� ���������� ��Ÿ���ϴ�.
   - �������� ȭ�� ����
     - ���������� �������� ���еǾ� ������ �� ���(Node)���� �ش�Ǵ� ������ �׷����·� ��ġ�� �ֽ��ϴ�.
     - ���(Node)���� ����� ����(Edge)�� ǥ�õǸ� Parent-Child ���踦 ǥ���ϰų� ������ �� �帧�� ��Ÿ���ϴ�.
     - ��������� ��Ÿ�����͸� Ȯ���ϴ� ����� ��� �� ������ Ŭ���Ͽ� ��Ÿ���� ���������� ���� ���� Ȯ���� �� �ֽ��ϴ�.
   - ��Ʈ��ũ ���� ����
     - ABLESTACK-Skydive Agent�� �� ��Ʈ��ũ ������ �����ϴ� ���� Probe�� �̷���� ������ �⺻������ NetLINK, LibVirt, LLDP, Socket Information Probe�� Ȱ��ȭ �Ǿ��ֽ��ϴ�.
     - NetLINK Probe�� ���� ��Ʈ��ũ ������ ������Ʈ �ֱ�� 30���Դϴ�.
     - ����ġ�� ������ LLDP Probe�� ���� �����Ǵµ� ���� ����ġ���� LLDP ����� Ȱ��ȭ �Ͽ��� �մϴ�. ����ġ�� LLDP ������ �۽��ϸ� ABLESTACK-Skydive�� Probe�� �� Host�� ��ġ�� "lldpd ��Ű��"�� Ȱ���Ͽ� ������ �����Ͽ� ����ڿ��� �����մϴ�.

  - ����ġ ���� ����
    - ABLESTACK-Skydive�� LLDP�� ����Ͽ� ����ġ ������ �����ϰ� �м��� �� �ֽ��ϴ�. �̸� ���� �߰� ������ �ʿ��մϴ�.
    - ������ �� ����ġ�� LLDP(Link Layer Discovery Protocol) Ȱ��ȭ
      - Mellanox
        ~~~
        admin [standalone: master] > enable
        admin [standalone: master] # configure terminal
        admin [standalone: master] (config) # lldp				## lldp Ȱ��ȭ
        admin [standalone: master] (config) # show lldp local	## lldp Ȱ��ȭ Ȯ��
        ~~~      
      - Cisco
        ~~~
        switch# configure terminal
        switch(config)# lldp run								## lldp Ȱ��ȭ
        switch(config)# show lldp								## lldp Ȱ��ȭ Ȯ��
        ~~~
    - lldpd ���� ����
      - ABLESTACK-Skydive Agent�� ��ġ�� �� ȣ��Ʈ���� lldpd ���񽺸� ����� �մϴ�.
        ~~~
        systemctl restart lldpd.service
        ~~~

 - Ʈ���� ĸó
   - ĸó�� ���۵Ǹ� ĸó�� �������̽��� ĸó�� Ȱ�� �������� ��Ÿ���� 'ī�޶� ���'�� ǥ�õ˴ϴ�.
   ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-capture-camera.png?raw=true)<br/><br/>
   
   - ĸó�� �����ϱ� ���ؼ��� �ش� ��带 ������ ���콺�� Ŭ���Ͽ� "Capture"�� �����ϰų� ���� ��ܿ� ��ġ�� "ī�޶� ���"�� Ŭ���Ͽ� �����մϴ�.
   ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-capture-mouse-click-button.png?raw=true)
   ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-capture-button.png?raw=true)
   <br/><br/>

   - ĸó�� �� �� �ִ� ��� ������ �ֽ��ϴ�. Node�� Ÿ���� device, bridge, vlan�� ��� ĸó ����� Ȱ��ȭ �� �� �ֽ��ϴ�.
   - ĸó ������ ĸó�� Ȱ��ȭ�� ��带 ������ ���콺�� Ŭ���Ͽ� "Delete Captures"�� �����ϰų� UI ������ �ִ� ���ڵ�� �޴� �� "Captures"�� Ŭ���� �� ������ ĸó�� �����Ͽ� �����մϴ�. ĸó�� �������� �ʰ� ��Ʈ��ũ ������ ����Ǿ� ���񽺸� ������� ��� Error �޽����� �߻��� �� �����Ƿ� ������� �ʴ� ĸó�� ������ �����Ǿ�� �մϴ�.
   
- Flow table
    - ĸó�� ���������� Ȱ��ȭ�Ǹ� ���� ���ڵ�� �޴��� Flow table�� ��Ÿ���ϴ�.
    - Flow table�� �ε��Ǵ� �� �������� ���� 10�� �̻��� �ð��� �ɸ��� ��쵵 �ֽ��ϴ�.
    - Flow table �޴� ��ܿ� "View Columns"�� Ŭ���ϸ� ���̺� ǥ���� �÷��� ������ �� �ֽ��ϴ�.
    - Flow table�� ��� ���� Flow table�� ���� ĸó�� Ȱ��ȭ�� ��Ʈ��ũ(Network A)���� Network B ������ ���Ἲ Ȯ�� �Ǵ� ������ �̵��� ���� Ȯ���� �� �ֽ��ϴ�.<br/><br/>
    ![](https://github.com/stardom3645/wiki/blob/main/skydive-img/ablestack-skydive-flowTable.png?raw=true)
    



