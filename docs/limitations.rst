.. _limitations:

===================
Runtime limitations
===================

- Programs cannot exceed 750KB in size.
- Inputs to jobs cannot exceed 64MB in size.

The effective timeout of a Qiskit Runtime job is decided by the program cost, as long as it is under the maximum specified below. Otherwise, the maximum is used.

<table>
<thead>
  <tr>
    <th></th>
    <th colspan="2">Public Program (IBM Only)</th>
    <th colspan="2">Private Program</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td>Premium User</td>
    <td>Open User</td>
    <td>Premium User</td>
    <td>Open User</td>
  </tr>
  <tr>
    <td>Simulated Device</td>
    <td>3h</td>
    <td>1h</td>
    <td>3h</td>
    <td>1h</td>
  </tr>
  <tr>
    <td>Real Device</td>
    <td>8h</td>
    <td>4h</td>
    <td>8h</td>
    <td>2h</td>
  </tr>
</tbody>
</table>

.. Hiding - Indices and tables
   :ref:`genindex`
   :ref:`modindex`
   :ref:`search`
